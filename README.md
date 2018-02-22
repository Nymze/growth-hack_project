# INSILICO Landing
#### By Arnaud Meneroud
<br/>
<br/>
Pour commencer voici la Landing page sur laquelle vous pourrez vous inscrire à notre newletter: https://damp-thicket-67928.herokuapp.com/.
<br/>
Nous avons découpé le travail du jour en 4 étapes:

* Création de la base de l'app adaptée avec un template [html5up](https://html5up.net/).
* Scrapping des Lycées et Universitées de la région londonienne afin de créer une Database de prospects.
* Sauvegarder notre base de donnée dans une liste [Maichimp](https://us17.admin.mailchimp.com/).
* Envoi d'un mail comportant un bouton qui redirige vers notre notre *Landing page* à toute notre liste.
<br/>
#### Remarque:
Le scrappeur fonctionne quand il s'agit de récupérer les données, mais nous n'avons pas encore trouvé comment rediriger ces données directement dans une liste Mailchimp. Work in progress...<br/>
<br/>
Concernant MailChimp, nous avons créé un **Signup Form - embbeded** depuis la liste. Cela nous a permis de récupérer le code de ce *form* et de l'intégrer dans notre section "five" de notre `index.html.erb`. 

