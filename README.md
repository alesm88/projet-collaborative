<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>projet collaborative</title>
</head>
<body>
    <h1>Projet collaborative</h1>
    <p>Projet pour la création d'un site web simple. Chaque groupe ajoutera une partie différente
        du contenu.</p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Formulaire de Contact</title>
</head>
<body>
    <h1>Contactez-nous</h1>
    
    <form action="/envoyer-message" method="POST">
        <label for="nom">Nom :</label><br>
        <input type="text" id="nom" name="nom" required><br><br>

        <label for="email">Email :</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="telephone">Téléphone :</label><br>
        <input type="tel" id="telephone" name="telephone"><br><br>

        <label for="message">Votre message :</label><br>
        <textarea id="message" name="message" rows="5" cols="40" required></textarea><br><br>

        <button type="submit">Envoyer</button>
    </form>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Page avec Footer</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .content {
            flex: 1;
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        footer a {
            color: #4CAF50;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Bienvenue sur mon site</h1>
        <p>Voici le contenu principal de la page.</p>
    </div>

    <footer>
        © 2025 MonSiteWeb - <a href="/mentions-legales">Mentions Légales</a> | <a href="/contact">Contact</a>
    </footer>
</body>
</html>

```markdown
# Projet Collaborative
Projet pour la création d'un site web simple. Chaque groupe ajoutera une partie différente
du contenu.
```
