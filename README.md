<h1 align="center">Cognitive Ai Service</h1>


### Introdução

Este repositório foi criado para o desafio de projeto proposto no curso Microsoft - Fundamentos de IA (Azure AI-900), promovido pela DIO.

O objetivo do desafio é utilizar os modelos de reconhecimento de imagem e documentos disponiveis no [Portal Azure Vision Studio](https://portal.vision.cognitive.azure.com).

##
> 📢 **Licença**
> <br/> As imagens utilizadas neste projeto foram obtidas do [Unplash](https://unsplash.com) e seguem sua [Licença padrão](https://unsplash.com/pt-br/licença).
> <br/> As imagens não devem ser utilizadas para fins comerciais sem modificações significativas.
##

### Passo à passo

1. Criar o serviço no Azure AI Studio
Para começar, siga o guia oficial: [Iniciando no Azure ai Studio](https://learn.microsoft.com/pt-br/azure/ai-services/computer-vision/overview-vision-studio#get-started-using-vision-studio)

2. Criar um serviço no Portal da Azure
    - Acesse o [Portal da Azure](https://portal.azure.com) e clique em Criar um recurso..
     
   ![criar_serv](https://github.com/user-attachments/assets/1e2cbea1-2f79-4baf-ae4d-6e3d3fad6259)

     - Na barra de pesquisa, procure por **Azure Ai Services**, selecione o serviço e clique em **criar**...
       
   ![criar_serviço](https://github.com/user-attachments/assets/6affae05-9441-46e2-8898-cd2bdfe1b00b)

3. Após criar o serviço iremos acessar o portal do [Azure Vision Studio](https://portal.vision.cognitive.azure.com)

4. Visualizar todos os serviços disponíveis
<br/> No portal, clique em Visualizar todos os serviços.
   ![visualizar_servicos](https://github.com/user-attachments/assets/a83e628e-ad17-4c9c-8308-2caac99daeac)

5. Selecionar o serviço criado
<br/> Localize o serviço que você criou e clique em **Selecionar como recurso padrão**
![selecionar_servico](https://github.com/user-attachments/assets/6681206c-fe09-4b29-ab55-c72bb2535d5e)

6. Finalizar a seção
<br/> Após selecionar o serviço, clique no **X** para sair

7. Escolher o serviço de legendas para imagens e testar o modelo
<br/> Agora, selecione o serviço que adiciona legendas em imagens
![escolher_servico](https://github.com/user-attachments/assets/d9b85909-4e73-49b0-9364-6c1cc7aec127)


8. Configurar o modelo 
<br/> Dentro do modelo, marque a **checkbox** para ativá-lo. 
![marcar_check](https://github.com/user-attachments/assets/0da969a6-adbc-4c7e-8b3d-502d69d2aa29)

9. Selecionar um exemplo ou importar uma imagem
<br/> Você pode escolher entre os exemplos disponíveis ou importar sua própria imagem. 
![selecionar_arquivos](https://github.com/user-attachments/assets/aeca481c-7382-44aa-9a03-7bec200cb1cf)


> ***Importante ⚠***:
> <br/> Para utilizar o modelo, eu importei uma imagem do meu computador

  - Após escolher a imagem, aguarde o processamento.
  - O serviço irá gerar uma legenda automaticamente para a imagem.
![man_using_laptop](https://github.com/user-attachments/assets/07d0cd3e-7b09-47dd-acd2-73d698e7a590)

## 

### 📌 Mais informações
   - Além do modelo de legendas, você também pode explorar outros modelos, como o de reconhecimento de imagem.
  ![three_faces_output](https://github.com/user-attachments/assets/b3a00007-a47a-4ffe-ac17-ce6ac5c8ef12)

  - Para entender melhor o funcionamento e as possibilidades, confira a documentação oficial:
    - 📖 [Documentação do Computer Vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/)
  
  - Veja mais exemplos de como utilizar os modelos na prática:
    - 💡 [Azure-samples](https://github.com/Azure-Samples/azure-ai-vision)
    
