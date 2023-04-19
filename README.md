## Testes de API com ServeREST

Atividade avaliativa do módulo 13 do curso Engenheiro de Qualidade de Software da EBAC. 

### Consumindo o ServeRest

Execute o seguinte comando no terminal:

`npx serverest@latest`

### Rodando os testes

Faça o import da collection no Postman e rode a collection conforme vídeo abaixo

![2023-04-19_00h30_24](https://user-images.githubusercontent.com/87156630/232959967-e4998640-ef9b-48f5-95e2-1d5bb977c704.gif)

### Utilizando o Newman HTML Report

Execute o seguinte comando no terminal para instalar:

`npm install -g newman-reporter-htmlextra`

Execute o seguinte comando no terminal para gerar o relatório:

`newman run TesteServeREST.postman_collection.json -r htmlextra`

![2023-04-19_00h33_32](https://user-images.githubusercontent.com/87156630/232960407-d4a16c37-4b52-4cd4-b843-f71b2771bcae.gif)
