# P-gina-de-login
Página totalmente feita em html puro

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
</head>
<body>

    <h1>Login</h1>

    <form>
        <label for="email">E-mail:</label>
        <br>
        <input 
            type="email" 
            id="email" 
            name="email" 
            placeholder="Digite seu e-mail"
            required
        >

        <br><br>

        <label for="senha">Senha:</label>
        <br>
        <input 
            type="password" 
            id="senha" 
            name="senha" 
            placeholder="Digite sua senha"
            required
        >

        <br><br>

        <button type="submit">Entrar</button>
    </form>

    <p>
        Esqueceu sua senha?
        <a href="#">Recuperar senha</a>
    </p>

    <p>
        Ainda não possui uma conta?
        <a href="#">Criar conta</a>
    </p>

</body>
</html>
