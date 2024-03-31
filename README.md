Claro, aqui está uma versão organizada dos comandos para serem postados no arquivo README.md:

```bash
# Configurações do Git
## Configurando usuário e email globalmente
git config --global user.name "leonardo25dev"
git config --global user.email "leonardofernandes22.pb@gmail.com"

## Gerando e adicionando chave SSH
ssh-keygen -t ed25519 -C "leonardofernandes22.pb@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

## Visualizando chave SSH pública
cat ~/.ssh/id_ed25519.pub

# Clonando repositórios
git clone git@github.com:Leonardo25dev/html.git
git clone git@github.com:Leonardo25dev/Java-script.git

# Edição de código
## Abrindo editor de código (Visual Studio Code)
code .

# Gerenciamento de mudanças no Git
git add .
git status
git commit -m "criado o texto"
git push
```

Espero que isso ajude! Se precisar de mais alguma coisa, não hesite em perguntar.
