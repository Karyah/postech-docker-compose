# Testando o projeto:

## Rodar Docker Compose
A partir do arquivo docker-compose.yaml é possível testar nosso projeto. Nele, existem todas as configurações de ambiente e imagens dos nossos projetos necessárias para rodar o nosso projeto como um todo.

### Como rodar o docker-compose.yaml?
- Baixar o arquivo docker-compose.yaml
- Abrir o terminal onde o arquivo foi baixado
- Rodar o comando ``` docker compose up -d ```

Como estamos subindo também as configurações de banco de dados, é necessário esperar aproximadamente 20 segundos (depois de startado) para que tudo já esteja funcionando!

### Como rodar o docker-compose.yaml no MAC
Para rodar o docker compose no MAC, será necessário realizar alterações no arquivo.
Deve ser acrescentado o atributo "platform: linux/amd64" em todas os containers. Por exemplo:

![image](https://github.com/user-attachments/assets/2d3215bc-7cb0-4f7d-adf1-40b37dc102e8)



## Testar endpoints com o Postman
- Baixar a coleção do postman disponível na pasta "Postman" desse repositório
- Procurar a aba de "importar" dentro do Postman em Collections

 ![image](https://github.com/user-attachments/assets/4e3a7e13-2f75-4435-a207-9a3abf01f8bd)

- Clicar em "Import" ou "Importar"
- Selecionar o arquivo de coleções baixado.

![image](https://github.com/user-attachments/assets/47cfb1b6-f934-4dd7-bc21-e14e0ce71d25)

- E a coleção já estará pronta!
  
![image](https://github.com/user-attachments/assets/8992e5c9-a874-4b9e-80f6-d0836b065ad2)
