index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Criptografia e Hash com Python</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <nav class="navbar">
            <h1>🔐 CriptoPython</h1>

            <div class="menu">
                <a href="#inicio">Início</a>
                <a href="#conceitos">Conceitos</a>
                <a href="#exemplos">Exemplos</a>
                <a href="#conclusao">Conclusão</a>
            </div>
        </nav>
    </header>

    <main>

        <!-- INÍCIO -->
        <section id="inicio" class="hero">

            <div class="hero-text">
                <span class="tag">PROJETO DE CONCLUSÃO</span>

                <h2>
                    Proteção de informações:
                    <span>Criptografia e Hash com Python</span>
                </h2>

                <p>
                    Um resumo interativo dos principais conceitos estudados
                    durante o curso, mostrando como as informações podem ser
                    protegidas em ambientes digitais.
                </p>

                <a href="#conceitos" class="button">
                    Conhecer os conceitos
                </a>
            </div>

            <div class="lock">
                🔐
            </div>

        </section>


        <!-- CONCEITOS -->
        <section id="conceitos" class="section">

            <div class="section-title">
                <span>01</span>
                <h2>Principais conceitos</h2>
            </div>

            <div class="cards">

                <article class="card">
                    <div class="icon">🔢</div>

                    <h3>Troca de números</h3>

                    <p>
                        A troca de valores é um exemplo simples de lógica
                        utilizada na programação e ajuda a compreender como
                        os dados podem ser manipulados.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">🔤</div>

                    <h3>Cifras</h3>

                    <p>
                        As cifras transformam informações utilizando regras
                        específicas. Um exemplo clássico é deslocar letras
                        dentro do alfabeto.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">🖥️</div>

                    <h3>Tabela ASCII</h3>

                    <p>
                        A tabela ASCII associa caracteres a valores numéricos,
                        permitindo compreender como letras e símbolos são
                        representados digitalmente.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">#️⃣</div>

                    <h3>Hash</h3>

                    <p>
                        Hash transforma uma informação em uma representação
                        de tamanho definido. É muito utilizado para verificar
                        integridade e proteger informações.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">🧂</div>

                    <h3>Salt (tempero)</h3>

                    <p>
                        O salt é um valor adicional utilizado junto ao dado
                        antes do processo de hash, aumentando a proteção
                        contra ataques baseados em hashes conhecidos.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">💾</div>

                    <h3>Memória</h3>

                    <p>
                        A quantidade de espaço disponível na memória influencia
                        a maneira como os dados são armazenados e processados
                        pelos computadores.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">01</div>

                    <h3>Binário</h3>

                    <p>
                        Os computadores trabalham fundamentalmente com dois
                        estados, representados pelos valores 0 e 1.
                    </p>
                </article>


                <article class="card">
                    <div class="icon">0x</div>

                    <h3>Hexadecimal</h3>

                    <p>
                        O sistema hexadecimal utiliza 16 símbolos e facilita
                        a representação de valores binários de maneira mais
                        compacta.
                    </p>
                </article>

            </div>

        </section>


        <!-- EXEMPLOS -->
        <section id="exemplos" class="section dark-section">

            <div class="section-title">
                <span>02</span>
                <h2>Exemplos práticos</h2>
            </div>


            <div class="example-container">

                <div class="example">

                    <h3>🔄 Troca de números em Python</h3>

                    <pre><code>numero1 = 10
numero2 = 20

numero1, numero2 = numero2, numero1

print(numero1)
print(numero2)</code></pre>

                    <p>
                        Nesse exemplo, os valores das duas variáveis são
                        trocados sem a necessidade de uma terceira variável.
                    </p>

                </div>


                <div class="example">

                    <h3>🔐 Hash com Python</h3>

                    <pre><code>import hashlib

senha = "minha_senha"

hash_senha = hashlib.sha256(
    senha.encode()
).hexdigest()

print(hash_senha)</code></pre>

                    <p>
                        O módulo <strong>hashlib</strong> disponibiliza
                        algoritmos de hash, como o SHA-256.
                    </p>

                </div>


                <div class="example">

                    <h3>🔤 Convertendo texto para ASCII</h3>

                    <pre><code>texto = "Python"

for caractere in texto:
    print(ord(caractere))</code></pre>

                    <p>
                        A função <strong>ord()</strong> retorna o valor
                        numérico correspondente a um caractere.
                    </p>

                </div>

            </div>

        </section>


        <!-- FLUXO -->
        <section class="section">

            <div class="section-title">
                <span>03</span>
                <h2>Como a informação é protegida?</h2>
            </div>

            <div class="flow">

                <div class="flow-item">
                    <strong>01</strong>
                    <span>Informação</span>
                </div>

                <div class="arrow">→</div>

                <div class="flow-item">
                    <strong>02</strong>
                    <span>Representação digital</span>
                </div>

                <div class="arrow">→</div>

                <div class="flow-item">
                    <strong>03</strong>
                    <span>Criptografia / Hash</span>
                </div>

                <div class="arrow">→</div>

                <div class="flow-item">
                    <strong>04</strong>
                    <span>Proteção</span>
                </div>

            </div>

        </section>


        <!-- CONCLUSÃO -->
        <section id="conclusao" class="conclusion">

            <div class="conclusion-content">

                <span class="tag">CONCLUSÃO</span>

                <h2>
                    Segurança digital começa pelo conhecimento.
                </h2>

                <p>
                    Durante o curso, foi possível compreender que as
                    informações utilizadas diariamente em sistemas digitais
                    precisam ser armazenadas e protegidas de maneira adequada.
                </p>

                <p>
                    Conceitos como criptografia, hash, salt, ASCII, números
                    binários e hexadecimais ajudam a entender o que acontece
                    com uma informação desde sua representação até seu
                    armazenamento.
                </p>

                <p>
                    Este projeto representa uma revisão dos conhecimentos
                    adquiridos e também um incentivo para continuar estudando
                    programação, segurança da informação e tecnologia.
                </p>

            </div>

        </section>

    </main>


    <footer>

        <h3>🔐 CriptoPython</h3>

        <p>
            Projeto desenvolvido como conclusão do curso
            "Proteção de informações: criptografia e hash com Python".
        </p>

        <p class="copyright">
            © 2026 - Projeto educacional
        </p>

    </footer>

</body>
</html>
style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #0b1120;
    color: #e5e7eb;
    line-height: 1.6;
}

/* NAVBAR */

header {
    position: sticky;
    top: 0;
    z-index: 1000;
    background: rgba(11, 17, 32, 0.95);
    border-bottom: 1px solid #1e293b;
}

.navbar {
    max-width: 1150px;
    margin: auto;
    padding: 18px 25px;

    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar h1 {
    color: #38bdf8;
    font-size: 22px;
}

.menu {
    display: flex;
    gap: 25px;
}

.menu a {
    color: #cbd5e1;
    text-decoration: none;
    transition: 0.3s;
}

.menu a:hover {
    color: #38bdf8;
}


/* HERO */

.hero {
    min-height: 85vh;
    max-width: 1150px;
    margin: auto;
    padding: 80px 25px;

    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 50px;
}

.hero-text {
    max-width: 700px;
}

.tag {
    display: inline-block;

    padding: 7px 13px;
    margin-bottom: 20px;

    border: 1px solid #0ea5e9;
    border-radius: 20px;

    color: #38bdf8;
    font-size: 12px;
    font-weight: bold;
    letter-spacing: 1px;
}

.hero h2 {
    font-size: clamp(40px, 6vw, 72px);
    line-height: 1.05;
    margin-bottom: 25px;
}

.hero h2 span {
    color: #38bdf8;
}

.hero p {
    color: #94a3b8;
    font-size: 18px;
    max-width: 650px;
    margin-bottom: 30px;
}

.button {
    display: inline-block;

    padding: 13px 22px;

    background: #0284c7;
    color: white;

    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;

    transition: 0.3s;
}

.button:hover {
    background: #0ea5e9;
    transform: translateY(-2px);
}

.lock {
    width: 250px;
    height: 250px;

    display: flex;
    justify-content: center;
    align-items: center;

    font-size: 110px;

    border: 1px solid #164e63;
    border-radius: 50%;

    background: radial-gradient(
        circle,
        #082f49,
        #0b1120
    );

    box-shadow: 0 0 80px rgba(14, 165, 233, 0.2);
}


/* SEÇÕES */

.section {
    max-width: 1150px;
    margin: auto;
    padding: 90px 25px;
}

.section-title {
    margin-bottom: 45px;
}

.section-title span {
    color: #38bdf8;
    font-weight: bold;
}

.section-title h2 {
    font-size: 38px;
    margin-top: 5px;
}


/* CARDS */

.cards {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.card {
    padding: 25px;

    background: #111827;

    border: 1px solid #1e293b;
    border-radius: 12px;

    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: #0ea5e9;
}

.icon {
    width: 50px;
    height: 50px;

    display: flex;
    align-items: center;
    justify-content: center;

    margin-bottom: 18px;

    background: #082f49;
    border-radius: 10px;

    color: #38bdf8;
    font-weight: bold;
    font-size: 20px;
}

.card h3 {
    margin-bottom: 10px;
}

.card p {
    color: #94a3b8;
    font-size: 14px;
}


/* EXEMPLOS */

.dark-section {
    max-width: none;
    background: #080d18;
}

.dark-section > .section-title,
.example-container {
    max-width: 1100px;
    margin-left: auto;
    margin-right: auto;
}

.example-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.example {
    background: #111827;
    border: 1px solid #1e293b;
    border-radius: 12px;
    padding: 25px;
}

.example h3 {
    margin-bottom:
