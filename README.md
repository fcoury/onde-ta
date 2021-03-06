<h1 align="center">
  <img src="images/logo.png" alt="onde-ta" width="300" />
</h1>

> Rastreie suas encomendas
![Build Status](https://travis-ci.org/filipelinhares/onde-ta.svg?branch=master)

<p align="center">
  <img src="images/preview.gif"  alt="onde-ta preview" width="49%" />
  <img src="images/output-example.png"  alt="onde-ta output preview" width="49%" />
</p>

## Install
```
$ npm install --global onde-ta
```

## Usage
```
$ onde-ta --help

  Como usar:
    $ onde-ta RE108441783BR

    Salvar e visualizar códigos de rastreio
    $ onde-ta RE108441783BR --save batman
    $ onde-ta batman

    Remover um código salvo
    $ onde-ta --remove batman
    $ onde-ta --clear

    Listar todos os códigos salvos
    $ onde-ta --list

  Opções
    -s, --save     Salva um código de rastreio com nome
    -r, --remove   Remove o código selecionado
    -c, --clear    Remove todos os códigos salvos
    -l, --list     Listar todos os códigos salvos com um nome
```

## Service
- [Correios Tracking](https://github.com/filipelinhares/correios-tracking)

## License
[MIT](LICENSE.md) © Filipe Linhares
