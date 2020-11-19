# Aula de git

### Configurando Git
```
git config --global user.name  [seu nome]
git config --global user.email [seu email]
git config --list
```
### Iniciando Repositório
```
git init
vim /etc/hosts
```
### Adicionar
127.0.0.1 teste1.local
127.0.0.1 teste2.local

### Subir as docker 
```
docker run -itd --name teste1 -h teste1 midianet/kube:1.0.0
docker run -itd --name teste2 -h teste2 midianet/kube:2.0.0
```

### Verificando IP
```
docker inspect teste1
docker inspect teste2
```

 v,ttttttttttttttt

### Voltando pra masterzzzzzz
```
git checkout master
```

### Realizando merge com a teste2
```
git merge teste2
```

### Commitando a master
```
git commit -m "merge com teste2"
```

### Reiniciando Apache
```
systemclt apache2 restart
```

### Acessando o site
http://teste2.local

### Apagando a branch local
git branch -d teste2

### Refazer tudo usando gitlab
apagar a pasta .git
```
rm -rf .git
git init
git remote add origin [caminho repo gitlab]
```





