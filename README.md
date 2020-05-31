<p align="center"><img src="https://github.com/francis-taylor/Timotty/blob/master/images.png" alt="Timotty"></p>
<p align="center"><a href="https://t.me/SuporteKbot">Kbot</a></p>
<p align="center"><strong>Versão 0.1.4</strong></p>

### <p align="center">Sistema de automatização de sinais KBOT</p>
* * *
### <p align="center">⚠️OBS: Não nos responsabilizamos por perdas, opere por sua conta e risco!</p>
* * *
* O KBOT conta com um sofisticado sistema de operações binárias para operar na corretora IQ Option e de fácil configuração a través da plataforma de bots do Telegram.

* * *
## <p align="center">Instalar</p>

1. Baixe o instador python no [site oficial](https://www.python.org/downloads/), escolha a versão de acordo com o sistema e arquitetura do seu processador.
2. Abra o arquivo e marque a opção `"[x] Add to path"`
3. Clique em instalar e aguarde a instalação.
4. Extraia o arquivo `kbot.zip` no local desejado.
5. Feche a pagina e abra a pasta do robô.
6. Abra o [Bot Father](https://t.me/BotFather) no telegram.
7. Clique em "começar"
8. Digite `/newbot` e envie.
9. Escolha um nome para o seu robô e envie.
10. Escolha um username para o robô e envie. OBS:(O usernave deve terminar com "bot", por exemplo: MeuBot ou Meu_Bot, caso o username já exista, terá que escolher outro.)
11. O bot ira te enviar uma mensagem, copie o **token** que ele irá enviar e coloque no arquivo `config.py`, no espaço **token="bot_api_key"**
12. Preencha as configurações seguindo as instruções dentro do arquivo.
13. Abra a pasta do robô e clique duas vezes em ``start``.
14. Abra o [Bot Father](https://t.me/BotFather) novamente e clique no link que ele retorna junto a mensagem.
15. Clique em começar e digite **/id** e envie.
16. Copie o ID e coloque no item `sudo=[seu_id_aqui]`, no arquivo `config.py`.
17. Feche o prompt de comando e clique novamente em start.
18. Abra o robô no telegram e digite **/start**.
19. Clique em configurações.

* * *
## <p align="center">Adicionar sinais</p>

1. Abra o arquivo ``"sinais"`` na pasta do robô.

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
## <p align="center">Ajuda</p>

 * Itens do arquivo config.py
 
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
      <td>A quantidade de gales por operação</td>
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
      <td>gale_pct</td>
      <td>O valor de multiplicação da aposta.</td>
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
## <p align="center">Suporte</p>
<p align="center"> <b>OBS:</b> <i>Em caso de erros, falhas, bugs ou dúvidas, contate o <a href="https://t.me/SuporteKbot"> suporte Kbot telegram</a>.</i></p>

<a href="https://www.facebook.com/feesnegocios/"><img src="facebook.jpg" width="20" title="Facebook"></a>

* * *
**Tenha Bons Trades!! :)**
