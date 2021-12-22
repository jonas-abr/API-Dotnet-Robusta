# ManagerAPI

<br><br>
<br>

<h3 align="center">Para poder rodar o projeto você precisa configurar algumas variaveis de ambiente</h3>
<br>
<p>Iniciar os segredos de usuários</p>
<pre>
dotnet user-secrets init
</pre>
<br>
<br>
<p>Configurar a string de conexão ao banco de dados</p>
<br>
<pre>
dotnet user-secrets set "ConnectionStrings:USER_MANAGER" "[STRING CONNECTION]"
</pre>
<br>
<br>
<p>Configurar dados de autenticação (JWT)</p>
<br>
<pre>
dotnet user-secrets set "Jwt:Key" "[JWT CRYPTOGRAPHY KEY]"
dotnet user-secrets set "Jwt:Login" "[JWT LOGIN]"
dotnet user-secrets set "Jwt:Password" "[JWT PASSWORD]"
</pre>
<br>
<br>
<p>Por fim você configura a chave de criptografia da aplicação</p>
<br>
<pre>
dotnet user-secrets set "Cryptography" "[CHAVE DE CRIPTOGRAFIA DA APLICAÇÃO]"
</pre>
<br>
<br>
<br>
<h3 align="center">Alguns comandos que podem ser úteis :)</h3>
<br>
<br>
<p>Listar todas os segredos de usuário da aplicação.</p>
<br>
<pre>
dotnet user-secrets list
</pre>
<br>
<br>
<p>Deletar um segredo de usuário da aplicação.</p>
<br>
<pre>
dotnet user-secrets remove "[CHAVE]"
</pre>
<br><br>
<br><br>
<br><br>
<p align="center">2021&copy;</p>
