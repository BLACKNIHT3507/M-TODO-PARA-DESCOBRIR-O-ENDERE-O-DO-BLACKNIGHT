function buscarCEP() {
    const cep = document.getElementById("cep").value;
 
        // Chamada da API ViaCEP
        fetch("https://viacep.com.br/ws/" + cep + "/json/")
        .then(res => res.json())
        .then(dados => {
          document.getElementById("rua").innerText = dados.logradouro || "";
          document.getElementById("bairro").innerText = dados.bairro || "";
          document.getElementById("cidade").innerText = dados.localidade || "";
          document.getElementById("estado").innerText = dados.uf || "";
         
        })
        .catch(() => {
          alert("CEP inválido");
        });
    }
