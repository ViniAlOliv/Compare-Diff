# Comparação de arquivos JSON e outros

### Tecnologias utilizadas:
- Git instalado na máquina
- Visual Studio Code

### Recursos de ajuda
- https://codebeautify.org/jsonviewer


## 1) Comparação de arquivos

### Dúvidas
- Podemos comparar todos os tipos de arquivos, assim como comparamos diferenças entre commits
- Deixe os arquivos mais bem organizados possíveis, como terem o mesmo nome e uma diferença, texto ou json ser legível e etc...


## 2) Como comparar os dois arquivos deste exemplo?
- Abrir o terminal (Terminal / Novo Terminal) no Menu superior do Visual Studio Code
- Verificar se no terminal está apontando o local correto. Caso contrário, digite 'cd Arquivos' no terminal para acessar a pasta arquivos.
- Verificar se o Terminal foi aberto como 'bash'****. Não pode ser PowerShell e nem Prompt*****


### 2 a) Caso eu queira apresentar a diferença no Visual Studio Code...
- Tenha os dois arquivos
- Selecione o primeiro arquivo, clique com o botão direito em cima do mesmo e 'Select to compare'
- Selecione o segundo arquivo, clique com o botão direito em cima do mesmo e 'Compare with selected'
- Será gerado um novo arquivo comparando os dois


### 2 b) Caso eu queira apresentar a diferança no Terminal...
- Devo então inserir o comando 'diff nomeDoArquivoAntigo.extensão nomeDoArquivoNovo.extensão'
- Ao realizar a ação acima, teremos as diferenças apresentadas no terminal


### 2 c) Caso queira somente criar um arquivo com essas diferenças
- Devo então inserir o comando 'diff nomeDoArquivoAntigo.extensão nomeDoArquivoNovo.extensão > nomeDoArquivo.txt'

- Será criado um arquivo de mesmo nome e formato dentro da pasta Arquivos


Espero poder te ajudar

By Vini - 12/2022