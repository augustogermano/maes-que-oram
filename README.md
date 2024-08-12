<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mães que Oram pelos Filhos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        header {
            background-color: #6c757d;
            color: white;
            padding: 20px;
            width: 100%;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 2em;
        }
        section {
            padding: 20px;
            max-width: 800px;
            width: 100%;
            box-sizing: border-box;
        }
        .welcome-message, .daily-message, .prayers, .testimonials, .contact-form {
            margin-bottom: 40px;
        }
        h2 {
            font-size: 1.5em;
            color: #495057;
            border-bottom: 2px solid #adb5bd;
            padding-bottom: 10px;
        }
        p {
            font-size: 1em;
            line-height: 1.6;
            color: #495057;
        }
        .daily-message {
            background-color: #e9ecef;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
        }
        .daily-message p {
            font-size: 1.2em;
            font-style: italic;
        }
        .contact-form label {
            display: block;
            margin-bottom: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ced4da;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #6c757d;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mães que Oram pelos Filhos</h1>
    </header>
    <section class="welcome-message">
        <h2>Bem-vindas!</h2>
        <p>Este é um espaço dedicado a todas as mães que, com fé e devoção, oram diariamente pelos seus filhos. Aqui, você encontrará mensagens bíblicas diárias, orações especiais e testemunhos inspiradores. Junte-se a nós nesta jornada de fé e amor.</p>
    </section>
    <section class="daily-message">
        <h2>Mensagem Bíblica do Dia</h2>
        <p>"Ensina a criança no caminho em que deve andar, e mesmo quando for idoso, não se desviará dele." - Provérbios 22:6</p>
    </section>
    <section class="prayers">
        <h2>Orações pelos Filhos</h2>
        <p>Aqui você pode encontrar diversas orações específicas para o bem-estar, proteção e crescimento espiritual dos seus filhos. Estas orações foram preparadas com base na Palavra de Deus e na experiência de muitas mães ao redor do mundo.</p>
    </section>
    <section class="testimonials">
        <h2>Testemunhos</h2>
        <p>Leia histórias de mães que tiveram suas orações respondidas e como a fé transformou suas vidas e as de seus filhos. Estes testemunhos são uma fonte poderosa de encorajamento para todas nós.</p>
    </section>
    <section class="contact-form">
        <h2>Entre em Contato</h2>
        <form>
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>
</body>
</html>
