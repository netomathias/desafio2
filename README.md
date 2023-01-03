# desafio2

## Notification API

A empresa **BackendGerador** está tendo de dificuldades no rastreio e visualização de suas contas anuais e para ajudar no controle de gastos foi solicitado pelo setor de negócio uma nova ferramenta capaz de notificar determinados usuários via email, quando o somatório das contas do ano for negativo! Para isso, hoje, o setor financeiro elabora uma planilha com os dados de entrada, saída e total do ano. A solução, portanto, deverá ser capaz de fazer uploads de arquivos(csv, xlsl) e salvar os dados num banco de dados para posterior consulta! No momento em que ocorre o salvamento, o sistema deverá ser capaz de notificar um usuário por email se o total do ano analisado for negativo. No template do email, deverá constar o valor negativo das contas!
A resposta da api será um JSON no seguinte modelo:

```
{
  success: true
}
```

em caso de erro, soltará uma exceção de acordo com o erro!

A API deverá ser desenvolvida com *Java 17* e as *boas práticas e codestyle adotados no Gerador do Devs*.
O banco fica a critério de dev.

Ao término do desafio, ele deverá estar no Github pessoal de cada um com acesso ao @Ivonir Mathias Neto!

Boa sorte!
