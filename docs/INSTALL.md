## Trabalhando com Jekyll

#### Dependências

* Ruby 2.6^
* Gem jekyll
  
#### instalação

```
sudo apt-get update -y && sudo apt-get upgrade -y
sudo apt-add-repository ppa:brightbox/ruby-ng
sudo apt-get update
sudo apt-get install ruby2.5 ruby2.5-dev build-essential dh-autoreconf
sudo gem update
sudo gem install jekyll bundler
jekyll -v
```

#### Criando novo projeto

```
sudo jekyll new minimal-blog
```

#### Ver infos do tema 

```
 bundle info minima
```

#### copiar arquivos do tema minimo

```
sudo cp -r /var/lib/gems/2.5.0/gems/minima-2.5.1/* .
```

#### Construindo projeto (build)

```
jekyll build / b
```

#### Rodar site

```
sudo jekyll server / s --trace
```

