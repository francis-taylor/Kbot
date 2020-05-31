# Kbot

### Sistema de automatização de sinais KBOT
* * *
### OBS: Não nos responsabilizamos por perdas, opere por sua conta e risco!
* * *
* O KBOT conta com um sofisticado sistema de operações binárias para operar na corretora IQ Option e de fácil configuração pelo telegram.
* * *
## Instalar
* * *
01) Baixe o instador python no [site oficial](https://www.python.org/downloads/), escolha a versão de acordo com o sistema e arquitetura do seu processador.
02) Abra o arquivo e marque a opção `"Add to path"`
03) Clique em instalar e aguarde a instalação.
04) Feche a pagina e abra a pasta do bot.
05) Abra o [Bot Father](https://t.me/BotFather) no telegram.
06) Clique em "começar"
07) Digite `/newbot` e envie.
08) Escolha um nome para o seu robô e envie.
09) Escolha um username para o robô e envie. OBS:(O usernave deve terminar com "bot", por exemplo: MeuBot ou Meu_Bot, caso o username já exista, terá que escolher outro.)
10) O bot ira te enviar uma mensagem, copie o **token** que ele irá enviar e coloque no arquivo `config.py`, no espaço **token="bot_api_key"**
11) Preencha as configurações seguindo as instruções dentro do arquivo.
12) Abra a pasta do Kbot e clique duas vezes em ``start``.
13) Abra o [Bot Father](https://t.me/BotFather) novamente e clique no link que ele retorna junto a mensagem.
14) Clique em começar e digite **/id** e envie.
15) Copie o ID e coloque no item `sudo=[seu_id_aqui]`, no arquivo `config.py`.
16) reinicie o robot.
17) Abra o robô no telegram e digite **/start**.
18) Clique em configurações.

* * *
## Adicionar sinais

1) Abra o arquivo ``"sinais"`` na pasta do robô.

* Os sinais seguem um padrão:

`VELA;PARIDADE;HORA:MINUTO:SEGUNDOS:ACAO`

``Ex: M1;EURUSD;00:00:00;PUT``

2) adicione os sinais, um abaixo do outro.

Ex:
```
M1;EURUSD;00:00:00;PUT
M1;EURUSD;01:00:00;CALL
M1;EURUSD;02:00:00;PUT
```

3) Salve o arquivo e feche a janela.

* * *
## Ajuda

 Itens do arquivo config.py

* **Key**        -> *Chave única de autenticação com o sistema Kbot.*
* **Aposta**     -> *Valor em reais (R$) que o bot vai apostar nas operações.*
* **Email**      -> *Seu email da IQ option.*
* **Senha**      -> *Sua senha IQ option.*
* **Conta**      -> *A conta em que deseja operar (REAL OU PRACTICE).*
* **martingale** -> *A quantidade de gales por operação.*
* **martingale1**-> *Valor de aposta do gale1.*
* **martingale2**-> *Valor de aposta do gale2.*
* **sudo**       -> *Número único de identificação Telegram, para o bot obedecer somente a você.*
* **gale_pct**   -> *O valor de multiplicação da aposta. (Padrão: 2.2)*
* **Stop_win**   -> *O valor de ganhos que o bot deve parar ao atingir.*
* **max_loss**  -> *O valor perdas que o bot deve parar ao atingir.*
* **user**       -> *Nome do usuario.*
* **email_log**  -> *Email de contato.*
* **token**      -> *Token Telegram Api Bot.*

* * *
## Suporte
**OBS:** *Em caso de erros, falhas, bugs ou dúvidas, contate o [suporte Kbot telegram](https://t.me/SuporteKbot).*

* * *
**Tenha Bons Trades!! :)**
