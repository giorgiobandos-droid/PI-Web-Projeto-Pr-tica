<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1"
    >

    <title>Introdução ao CSS</title>

    <link
        href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap"
        rel="stylesheet"
    > 
   

    <link
        rel="stylesheet"
        href="style.css"
    >
</head>

<body>

    <header class="topbar">

        <h1 id="titulo">
            Cadastro Acadêmico
        </h1>

        <p class="sub">
            Vamos aplicar CSS: seletores, cores, fontes e estilos básicos.
        </p>

    </header>

    <main class="container">

        <section class="card">

            <h2 class="destaque">
                Formulário
            </h2>

            <form action="#sucesso" method="post">

                <fieldset>

                    <legend>
                        Dados do Aluno
                    </legend>

                    <label for="nome">
                        Nome:
                    </label>

                    <input
                        type="text"
                        id="nome"
                        name="nome"
                        required
                    >

                    <label for="email">
                        E-mail:
                    </label>

                    <input
                        type="email"
                        id="email"
                        name="email"
                        placeholder="exemplo@email.com"
                    >

                    <label for="msg">
                        Mensagem:
                    </label>

                    <textarea
                        id="msg"
                        name="mensagem"
                        rows="4"
                    ></textarea>

                    <div class="acoes">

                        <button type="submit">
                            Enviar
                        </button>

                        <button
                            type="reset"
                            class="secundario"
                        >
                            Limpar
  
                        </button>


                    </div>

                </fieldset>

            </form>

            <div
                class="alerta"
                role="alert"
            >
                Exemplo de alerta: verifique os campos obrigatórios.
            </div>


            
        
            
        <div
            
        id = "sucesso"     
        class="sucesso"
        role="alert"
                  >
                 Cadastro realizado com sucesso!
        </div>
  

        </section>

    </main>

    <footer class="rodape">

        <small>
            Laboratório 03 - Introdução ao CSS
        </small>

    </footer>


<section>
    <h3>Grupo: Meio-Devs</h3>
    <h3>Integrantes:</h3>
    <p>Diego Batista Luglio | RA:260106808</p>
    <p>Giorgio Cavalcanti Bandos | RA:26010468</p>
    <p>Mauricio Cunha Tamayo | RA:26006517</p>
    <p>Tarsilla Helena Neves Pap | RA:26026449</p>
    <br>
    <h3>Respostas para as questões:</h3>
    <p>1. Sim, o CSS foi carregado corretamente.</p>
    <p>2. Ao mudar --cor-primaria, a cor do botão de envio mudou de azul para verde escuro.</p>
    <p>3. Após remover o link da fonte Roboto, o navegador usou a próxima fonte da lista declarada em font-family (no CSS), devido ao fato que Roboto não pôde ser baixada.</p>
</section>

</body>



</html>
