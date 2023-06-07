# API CEP

**[DEMO](https://angelolustosa.github.io/api_cep/)**

Criar um formulário utilizando o seguinte layout abaixo:

![image](https://github.com/angelolustosa/api_cep_fs14/assets/15823158/869cbad1-edfe-4aba-877f-98092e93f0ef)

- Pode-se utilizar bootstrap ou outra biblioteca de componentes.

1 - Ao carregar o formulario já deve carregar no campo UF, os estados utlizando a API https://servicodados.ibge.gov.br/api/v1/localidades/

2 - Ao digitar o CEP e apertar TAB deve ser consultado a API de cep https://viacep.com.br/ws/01001000/json/ deve  preencher os seguintes campos

![image](https://github.com/angelolustosa/api_cep_fs14/assets/15823158/15381df9-e6a5-4d91-b72e-5e6757adf9ef)

3 - Ao selecionar o estado do _response_ que vem da API do CEP, a localidade deve ser selecionada também através da API https://servicodados.ibge.gov.br/api/v1/localidades/estados/CE/distritos.

4 - [OPCIONAL] Fazer a ordenação dos inputs selects.

![image](https://github.com/angelolustosa/api_cep_fs14/assets/15823158/79f1b857-a161-4621-b587-35bcf6a68d47)

![image](https://github.com/angelolustosa/api_cep_fs14/assets/15823158/a454b8e3-b3ef-4811-94bb-eac859dcd1fa)

5 - Pulicar no GitHub Pages

