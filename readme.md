# Ambiente de Desenvolvimento Python


## Tutorial de instalação

Clone o repositório com:
```
git clone https://github.com/cwtshh/AmbientePadrao-Python.git
```
Após isso teremos os seguintes arquivos.

* .gitignore - arquivo usado para ignorar o venv (upar um venv no github não é uma boa ideia).
* requirements.txt - arquivo com os pacotes instalados no venv.

## 1- Com o repositório preparado, devemos criar um ambiente de desenvolvimento dentro da pasta que acabamos de clonar.

```
> python -m venv <nomeDoAmbiente>
```
Exemplo:
```
> python -m venv ambiente_padrao
```

## 2- Vamos acessar o bash do venv para sincronizar as bibliotecas com o repositório.

```
> .\<nome_do_ambiente>\Scripts\activate
```
Ou

```
> .\<nome_do_ambiente>\Scripts\activate.bat
```

## 3- Para instalar as bibliotecas usamos:

```
> pip install -r requirements.txt
```

## 4- Por ultimo mudamos o interpretador para o python presente no venv

### No VsCode
Pressione ctrl + shift + p e digite
```
> Select Interpreter
```







