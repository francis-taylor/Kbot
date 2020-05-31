<p align="center"><img src="https://github.com/francis-taylor/Timotty/blob/master/images.png" alt="Timotty"></p>
<p align="center"><a href="https://t.me/SuporteKbot">Kbot</a></p>
<p align="center"><strong>Versão 0.1.4</strong></p>

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

`VELA;PARIDADE;HORA:MINUTO:SEGUNDOS;ACAO`

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
 
<table>
  <thead>
    <tr>
      <td><strong>Objeto</strong></td>
      <td><strong>Descrição</strong></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>key</td>
      <td>Chave única de autenticação com o sistema Kbot.</td>
    </tr>
    <tr>
      <td>Aposta</td>
      <td>Valor para apostar em operações.</td>
    </tr>
    <tr>
      <td>email</td>
      <td>E-mail IQ Option.</td>
    </tr>
    <tr>
     <td>senha</td>
     <td>Senha IQ Option.</td>
   </tr>
    <tr>
      <td>conta</td>
      <td>A conta em que deseja operar (REAL OU PRACTICE).</td>
    </tr>
    <tr>
      <td>martingale</td>
      td>A quantidade de gales por operação</td>
    </tr>
    <tr>
      <td>martingale1</td>
      <td>Valor de aposta do gale1.</td>
    </tr>
    <tr>
      <td>martingale2</td>
      <td>Valor de aposta do gale2.</td>
    </tr>
    <tr>
      <td>sudo</td>
      <td>Número único de identificação Telegram, para o bot obedecer somente a você.</td>
    </tr>
    <tr>
      <td>gale_pct</td>
      <td>O valor de multiplicação da aposta. (Padrão: 2.2)</td>
    </tr>
    <tr>
      <td>sudo</td>
      <td>Número único de identificação Telegram, para o bot obedecer somente a você.</td>
    </tr>
    
   <tr>
      <td>sto_win</td>
      <td>O valor de ganhos que o bot deve parar ao atingir.</td>
    </tr>
    <tr>
      <td>stop_loss</td>
      <td>O valor de perdas que o bot deve parar ao atingir.</td>
    </tr>
    <tr>
      <td>token</td>
      <td>Api Telegram Bot Token.</td>
    </tr>
    <tr>
      <td>email_log</td>
      <td>Email de contato</td>
    </tr>
  </tbody>
</table>

* * *
## Suporte
**OBS:** *Em caso de erros, falhas, bugs ou dúvidas, contate o [suporte Kbot telegram](https://t.me/SuporteKbot).*

* * *
**Tenha Bons Trades!! :)**
