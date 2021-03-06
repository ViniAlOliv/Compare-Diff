# Comparação de arquivos de Swagger, Openapi, documentos e outros

## 1) Pegar informações de Swagger:

### 1 a) Caso eu use Swagger:
- Ao acessar o devido Swagger, abaixo do título, você verá um link de doc para toda a API. Acesse-a e copie tudo (Ou Ctrl + A e Ctrl + C)
- Acesse o site: https://codebeautify.org/jsonviewer
- Cole, ao lado esquerdo, todo o objeto (Crtl + V)
- Clique no botão 'Beautify' e, ao apresentar o resultado ao lado, clique no botão de download (logo acima ao lado de copiar)

- Sendo uma comparação, faça o mesmo com o documento que queira realizar esse compara.

DICA:
Obtenha o arquivo antes e depois da alteração, ou o de produção e o interno, que provavelmente estará mais atualizado.

### 1 b) Caso não tenha Swagger
- Isso funcionará também com um texto. Copie e crie um json, yaml ou txt da melhor forma a atender você.



## 2) Como comparar os dois arquivos?
- Instalar Visual Studio Code
- Pegar o arquivo "Swagger - Openapi Diff" e abrí-lo no Visual Studio Code (Arquivo / Abrir Pasta e selecionar a pasta)
- Copiar os arquivos .json ou .yaml para dentro da pasta 'Arquivos'
- Abrir o terminal (Terminar / Novo Terminal) no Menu superior do Visual Studio Code
- Verificar se o Terminal foi aberto como 'bash'****. Não pode ser PowerShell e nem Prompt*****
- Verificar se o terminal está apontando o local correto. Caso contrário, digite 'cd Arquivos'


### 2 a) Caso eu queira apresentar a diferença no Visual Studio Code...
- No explorador, dentro da pasta Arquivos, dê um clique com o botão direito do mouse no arquivo mais antigo e selecione 'Selecionar para comparar'
- No mesmo local, dê um clique com o botão direito do mouse no arquivo mais novo e selecione 'Selecionar para comparar'

- Ao realizar a ação acima, serão apresentadas as diferenças entre os dois arquivos no Visual Studio Code marcando em vermelho do que foi alterado


### 2 b) Caso eu queira apresentar a diferança no Terminal...
- Devo então inserir o comando 'diff nomeDoArquivoAntigo.extensão nomeDoArquivoNovo.extensão'

- Ao realizar a ação acima, teremos as diferenças apresentadas no terminal


### 2 c) Caso queira criar um arquivo com essas diferenças
- Devo então inserir o comando 'diff nomeDoArquivoAntigo.extensão nomeDoArquivoNovo.extensão > nomeDoArquivo.txt'

- Será criado um arquivo de mesmo nome e formato dentro da pasta Arquivos

Observação: 
- Sua formatação não será a melhor dos mundos, mas conterá todas as informações encontradas =)
- A inclusão de um título irá te ajudar a identificar o texto ;)




By Vini
