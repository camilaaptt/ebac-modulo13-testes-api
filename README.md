## Testes de API com ServeREST

Atividade avaliativa do módulo 13 do curso Engenheiro de Qualidade de Software da EBAC. 

### Consumindo o ServeRest

Execute o seguinte comando no terminal:

`npx serverest@latest`

### Rodando os testes

Faça o import da collection no Postman e rode a collection conforme vídeo abaixo

![2023-04-19_00h39_31](https://user-images.githubusercontent.com/87156630/232961299-b1f2795e-1cf6-4033-93bf-f0e98a5ceece.gif)

### Utilizando o Newman HTML Report

Execute o seguinte comando no terminal para instalar:

`npm install -g newman-reporter-htmlextra`

Execute o seguinte comando no terminal para gerar o relatório:

`newman run TesteServeREST.postman_collection.json -r htmlextra`

![2023-04-19_00h41_01](https://user-images.githubusercontent.com/87156630/232961329-624ee82a-262e-4a36-9a7e-9a2442d73d3f.gif)
