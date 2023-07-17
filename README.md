# AI-Python
AI-Python é uma API para chat entre um cliente de uma Pizzaria e a inteligência artificial. 
Ele usa a API openai.ChatCompletion para gerar respostas naturais e envolventes com base em um dado prompt e contexto. 
O cliente será atendido de forma totalmente autonoma e seu pedido será realizado e encaminhado para o despacho. 
Pode-se configurar a AI com diferentes modelos, como gpt-3.5-turbo, e personalizar o parâmetro de temperatura, que controla o grau de aleatoriedade da saída do modelo.

## Instalação
Para usar o AI-Python, você precisa ter o Python 3 instalado no seu sistema. Você também precisa instalar os seguintes pacotes:

openai
os
dotenv
Você pode instalá-los usando pip:

pip install openai
pip install os
pip install dotenv

Você também precisa ter uma chave de API do OpenAI, que você pode obter ([aqui](https://platform.openai.com/)). Você precisa armazenar sua chave de API em um arquivo .env no mesmo diretório do seu código. O arquivo .env deve ser assim:

OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx


Para usar o AI-Python, você precisa importar os módulos e definir algumas funções. Aqui está um exemplo de como fazer isso:


AI-Python requer o seguinte:

Python 3
openai
os
dotenv
Chave de API do OpenAI
