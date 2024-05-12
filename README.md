# third_chatbot-api_key_google

### Descrição

Este projeto consiste em um chatbot turístico sobre a cidade de Icó, Ceará, desenvolvido com base nos conhecimentos adquiridos nas Aulas 4 e 5 da Imersão IA 2ª Edição da Alura em parceria com o Google. O chatbot utiliza a API Key do Google para acessar o modelo de linguagem Gemini Pro e gerar respostas informativas e acolhedoras sobre a cidade. Além disso, o chatbot exibe imagens relacionadas à pergunta do usuário, buscando-as diretamente do Google Drive.

### Tecnologias Utilizadas

* **Python:** Linguagem de programação principal utilizada no desenvolvimento do chatbot.
* **Google Colab:** Ambiente de desenvolvimento em nuvem utilizado para codificar e executar o chatbot.
* **Google Generative AI SDK:** Biblioteca Python que permite a integração com o modelo de linguagem Gemini Pro.
* **Google Drive:** Serviço de armazenamento em nuvem utilizado para armazenar e acessar as imagens do chatbot.
* **Pillow (PIL):** Biblioteca Python para manipulação de imagens, utilizada para redimensionar e exibir as imagens.
* **Ipywidgets:** Biblioteca Python para criação de interfaces interativas no Google Colab, utilizada para construir a interface do chatbot.
* **Requests:** Biblioteca Python para realizar requisições HTTP, utilizada para baixar imagens diretamente da URL do Google Drive.

* ![image](https://github.com/teofilonicolau/third_chatbot-api_key_google/assets/97030160/614d0bd1-d4bf-4cea-a30b-2842f81c377f)



### Como Usar

1. **Clone o repositório:** `git clone https://github.com/teofilonicolau/third_chatbot-api_key_google.git`
2. **Abra o arquivo `main.ipynb` no Google Colab.**
3. **Configure a API Key do Google:** Insira sua API Key no código, substituindo o valor de `api_key`.
4. **Monte o Google Drive:** Execute a célula que contém o código `drive.mount('/content/drive')`.
5. **Execute o código:** Execute todas as células do notebook para iniciar o chatbot.
6. **Interaja com o chatbot:** Digite suas perguntas sobre Icó no campo de texto e clique em "Enviar".

7. ![image](https://github.com/teofilonicolau/third_chatbot-api_key_google/assets/97030160/d7b95c20-e5f9-4956-a31f-042bf53b487e)

![image](https://github.com/teofilonicolau/third_chatbot-api_key_google/assets/97030160/b0ae1b18-05d6-4861-970c-33476595f55c)



### Exemplo de Uso

**Usuário:** O que você pode me contar sobre a história de Icó?

**Chatbot:** Eita, bichim! Olha só o que eu descobri: *[Resposta do Gemini Pro sobre a história de Icó]* 

*[Imagem relacionada à história de Icó]*

### Observações

* Certifique-se de ter uma API Key válida do Google para utilizar o modelo de linguagem Gemini Pro.
* Ajuste os links das imagens no código para corresponder às suas imagens armazenadas no Google Drive.
* Sinta-se à vontade para personalizar o chatbot, adicionando mais perguntas e respostas sobre Icó.

### Autor

Teofilo Nicolau - https://github.com/teofilonicolau
