# [Azure Vision Studio](https://portal.vision.cognitive.azure.com/) :books: :pencil2:

## O que é? :book: :eyes:
[Azure Vision Studio](https://portal.vision.cognitive.azure.com/)  é uma plataforma de inteligência artificial desenvolvida pela Microsoft que oferece recursos avançados de visão computacional. Com o Azure Vision Studio, os desenvolvedores podem construir e implantar modelos de visão computacional personalizados de forma rápida e fácil, sem a necessidade de conhecimento profundo em aprendizado de máquina ou visão computacional.  

Essa plataforma permite que os usuários treinem modelos de visão computacional usando conjuntos de dados próprios, além de fornecer ferramentas para rotulação de dados, treinamento de modelos e avaliação de desempenho. Os modelos treinados podem então ser implantados em produção para realizar tarefas como detecção de objetos, classificação de imagens, reconhecimento de texto em imagens e muito mais.

O [Azure Vision Studio](https://portal.vision.cognitive.azure.com/) é parte do ecossistema Azure da Microsoft, o que significa que se integra perfeitamente com outras ferramentas e serviços da plataforma Azure, como armazenamento de dados, computação em nuvem e análise de dados. Isso torna mais fácil para os desenvolvedores criar soluções de visão computacional completas e escaláveis para uma variedade de casos de uso.

## Como utilizar a ferramenta: 👨🏽‍🏫👨🏽‍💻

Siga os seguintes passos:  
📕 Passo 1:
--
1. abra o portal do Azure em [https://portal.azure.com](https://portal.azure.com/?azure-portal=true) , entrando com a conta da Microsoft associada à sua assinatura do Azure.
2. **Create a resource**
- Categories: **AI + Machine Learning**
- Azure IA service: **Create**

![passo1](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/7bd492b6-7b85-4e65-993b-b1813f52f4b3)



-   **Resource group:** crie um novo ou selecione um resource criado previamente
-   **Region: East US** (custo de serviço mais barato que no Brasil)
-   **Name** nome do seu projeto
-   **Pricing tier: Standard S0**
-   Marca a caixa: **"By checking this box I acknowledge that I have read and understood all the terms below"**
-   **Review + create**

![passo2](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/1e2f55fb-4458-46f3-8cbb-f960597dd1ee)

- **Create**

![passo3](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/1c8194ea-2513-4757-8941-14488e4ef2ce)

📗Passo 2: 
--
1. Em outra guia do navegador, navegue até **Vision Studio** em [https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com/?azure-portal=true) .
2.  Entre com sua conta e certifique-se de localizar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.
3.  Na página inicial do Vision Studio, selecione **"View All Resources"**.
   
![passo4](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/2f373d51-b0b9-49d2-856f-e2281bd3ca9b)

5. Na página que abre **Selecione um recurso para trabalhar** ou **Select a resource to work with** , passe o cursor do mouse sobre o recurso que você criou acima na lista e marque a caixa à esquerda do nome do recurso e selecione **Selecionar como recurso padrão** ou **Select as default resource**

![passo5](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/f0c2af33-14d9-4fe8-8033-923bb977802a)

6.  Feche a página de configurações selecionando o **“x”** no canto superior direito da tela.
7.  Entre na aba **"Face"**
-   Selecione **"Detect faces in an image"**

![passo6](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/db69025a-0816-467b-b15b-1ae71d1c1f62)

-   Marque a caixa abaixo do texto **"Try it out"**
-   Carregue suas imagens para testar - (a aplicação exemplo detecta rosto, e se há uso de máscara ou não). **No exemplo, foi detectado máscara**
 
 ![imagem](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/blob/main/output/Resultadoimg2.png?raw=true)

Exitem outros opções como por exemplo: 

![passo7](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/36535b79-95b5-4214-b097-d0bec2fd310f)

**(Extrai texto impresso e manuscrito de imagens e documentos para idiomas suportados)**.  
Exemplo:

![imagem](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/blob/main/output/Capturadetextoimg8.png?raw=true)

outra opção é a:
![passo8](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/assets/96626042/90340ffc-5a77-4832-8c86-9ebff3cc3c65)

**(gerar uma frase legível por humanos que descreva o conteúdo de uma imagem)**.  
Exemplo:
![imagem](https://github.com/ghrocha/DIO-Microsoft-Azure-AI-Fundamentals2/blob/main/output/Legendadaimg4.png?raw=true)


Comentário sobre a aplicação que foi utilizada:🌐📃✏️
--
É uma ferramenta poderosa e muito incrível, porém em determinadas imagem apresentou um erro. Esse erro se deu quando solicitei que a IA fizesse a legenda da imagem. O erro está presente no arguivo: **Legendadaimg3.png; Legendadaimg8.png**. Em alguns resultados poderia ter complementado, como foi no caso da **Legendadaimg9.png** é uma foto de uma igreja e a IA detectou que era somente um prédio.  
Foi muito incrivel e impressionante o poder que essa IA possui. 

😄😁😆👾👻  
--
Estruturado e organizado por Gustavo Henrique.
