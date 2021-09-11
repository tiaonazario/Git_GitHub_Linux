# Git GitHub Linux
Comandos usados na Instalação do Git e GitHub no Linux

# Comandos para instalação do Git

## Atulização dos pacotes
```powershell
sudo apt-get update
```
## Instalar o Git
```powershell
sudo apt-get install git
```
> O comando `clear` limpa a tela do terminal, o `ls` mostra os arquivos do diretorio e `ls -a` mostra os diretorios ocultos

## Configurar Usuário e E-mail
```powershell
git config --global user.name "usuario"
git config --global user.email "email"
```
> Com isso um arquivo, `.config`, oculto foi criado. Se usar `cat .gitconfig` ele mostra os parametros usuario e email que foram configurados anteriormente.

## Clonar repositório
```powershell
git clone https://github.com/usuario/repositorio
```
> Lembrar de substituir os campos `usuario` e `repositorio` para que não ocorra erro.

> Lembrar de usar o código de clonagem do reppsitório já na pasta que deseja.

## Status do repositório
```powershell
git status
```
> O nome já é autoexplicativo

## Adicionar arquivo no repositório Git
```powershell
git add arquivo
```

## Empurar arquivo ao GitHub
```powershell
git commit -m "Comentário"
git push
```
> Na primeira vez é preciso autenticar. No caso fornecer a `senha` e `usuario`.



