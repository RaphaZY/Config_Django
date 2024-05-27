# Config_Django
Para utilizar este passo-a-passo é necessario, configurar o banco de dados no setup/settings.py, 


## 0- Criação de VENV e instalação do Django:
<b>0.0-</b> Código para criar a VENV "python -m venv 'nome_do_ambiente_virtual': "
```bash
python3 -m venv igor
```
<b>0.1-</b> Ativando a VENV windows "nome_da_venv\Scripts\activate":
```bash
 C:\python\Django> .\igor\Scripts\activate 
```
<b>0.2-</b> Verificando se a VENV está ativa pelo <b>VSCode</b>:<br>
    - Caso a sua Venv esteja ativada, você vai verificar o nome dela na frete do caminho da pasta igual à imagem abaixo. 
    <br><br>
![venv](https://github.com/IMNascimento/DjangoSenai/assets/28989407/424b222b-40ea-48b6-8568-ff43cf9e99d7)
<br><br>
- Agora para você voltar e criar um servidor igual basta utilizar o comando "pip install -r nome_do_arquivo.txt"
```bash
(igor)C:\python\Django> pip install -r requeriments.txt
```

dicas para criar um arquivo imagem e utilizar o media faça assim  exemplo
 path = models.ImageField(upload_to="imagens/")