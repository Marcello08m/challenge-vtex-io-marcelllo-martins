# Desafio M3 Academy - VTEX IO 

## Configuração do inicial

1. Instale as dependências do projeto

```bash
yarn
```

2. Faça o login na VTEX na agencia Magma 

```bash
vtex login agenciamagma
```

3. Crie um workspace de desenvolvimento. 
Recomendamos seguir o padrão: `m3academy<nome>`. so e permitido o uso de letras minusculas e números.

```bash
vtex use m3academyanabrunasouza
```

## Desenvolvimento

1. Inicie o projeto

```bash
vtex link
```

2. Rode o gulp para compilar os arquivos

```bash
yarn scss
```

3. Abrar o seu workspace no navegador

```bash
vtex browse
```

## Problemas frequentes

### As vezes pode acontecer de bugar o link do projeto. Para resolver isso, rode o comando abaixo que vai desfazer o link e depois rode o comando de link novamente.

```bash
vtex unlink --all

vtex link
```


