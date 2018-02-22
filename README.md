# INSILICO Landing
#### By Arnaud Meneroud
<br/>
<br/>
Pour commencer voici la Landing page sur laquelle vous pourrez vous inscrire à notre newletter:  https://insilico-virtual.herokuapp.com/. 
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
#### MailChimp:
Concernant MailChimp, nous avons créé un **Signup Form - embbeded** depuis la liste. Cela nous a permis de récupérer le code de ce *form* et de l'intégrer dans notre section "five" de notre `index.html.erb`. 
Il suffit de lui donner les classes que notre template bootstrap comportait déjà, pour que notre signup formulaire rentre dans les thématiques de notre landing page.
<br/>
En parallèle, nous avons importé les adresses mails scrappées précédemment, de notre base de donnée excel à la liste MailChimp, qui nous permettra plus tard d'effectuer une campagne d'emails.<br/>
Ceci étant fait, nous avons donc:
* Une base de donnée avec pleins d'emails d'universitées londoniennes, pour pouvoir promouvoir la Réalité augmentée si chère à @Arnaud.
* Un email soigneusement élaboré par @Elodie, qui comporte des vidéos, et un bouton qui redirige vers notre landing Page au click. Pour le voir...souscrivez c'est par [ici](https://damp-thicket-67928.herokuapp.com/) ;).
<br/>
<br/>
Voilà, ça manque d'automatismes, mais on a fait avec nos armes. Si vous aviez vu la sensation de victoire que l'équipe a connu quand le bouton suscribe s'est affiché comme souhaité...<br/>
Sur ce, n'hésitez pas à visiter le site de @Nymze: https://insilico.uk/vr-training.
<br/>
<br/>
Force et honneur.


