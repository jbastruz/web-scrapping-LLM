Ce notebook est un essi sur l'utilisation de Mistral.AI dans le cadre d'une veille informationnelle sur internet.
Le but est de récupérer des articles sur internet et d'en faire un résumé en utilisant `mistral.ai`, puis de les envoyer par e-mail en format HTML généré par `Mistral.ai`

le code se découpe en 3 parties:

- récuperation des articles via url avec `BeautifulSoup`
- génération de résumé avec `Mistral.AI`
- génération du contenu HTML pour l'envoyer par e-mail automatisé via `Mistral.AI`
- envoi du message par e-mail

nous d'étaillerons le code pas à pas dans le reste du notebook.
