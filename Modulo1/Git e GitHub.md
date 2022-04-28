Git
Essa ferramenta não trabalha GUI (graphic user interface) como nós estamos acostumados a usar aplicativos. Ele funciona por CLI (comand line interface). Na verdade, o novo git tem sim uma GUI, mas não ensinaram no curso porque querem que a gente aprenda do jeito tradicional e disseram que isso vai ajudar a gente a se acostumar quando for trabalhar com telas cheias de linhas de códigos (basicamente foi isso. Obrigado, Perkles).
Como o Git funciona
SHA1 - Algoritmo de encriptação. ele vai embaralhar seu arquivo. Para que você tenha uma ideia do nível de segurança, se você escrever um texto em word e encriptar, ele vai  devolver um conjunto de caracteres. Se vc entrar no arquivo, mudar 1 caracter, salvar e depois encriptar de novo, ele vai entregar outro conjunto de códigos. E se você pegar esse arquivo alterado, desfazer a mudança que você fez, salvar e encriptar mais uma vez, o Git vai devolver o primeiro conjunto de caracteres que vo^ce recebeu.
Objetos Fundamentais
Blob - contém metadados do git.
Tree - armazena os blobs. Tem os seus próprios metadados e guarda o nome do arquivo.
Commit - junta tudo o que há. Ele também aponta uma Tree e 1 parente (que é o último commit realizado antes dele), aponta autor, mensagem e possui um carimbo de tempo da sua criação.

Para iniciar um versionamento:
git init
git add (e o nome do que queres adicionar. use * para adicionar tudo no diretório onde estiver)
git commit -m "" (para comitar e fazer um comentário dentro da string.

para enviar o versionamento
git status (verificar se tudo o que você queria foi adicionado)
git push origin main (empurrar para a o repositório remoto sua versão)

puxar verionamento
git pull origin main

clonar repositório
copie o endereço no github
entre no Git no lugar onde vc quer salvar o repositório
git clone *URL*
