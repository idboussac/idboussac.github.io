---
layout: page
title: FAQ
permalink: /faq/
---

<head>
 <link rel="stylesheet" href="//code.jquery.com/ui/1.10.4/themes/smoothness/jquery-ui.css">
   <script src="//code.jquery.com/jquery-1.10.2.js"></script>
   <script src="//code.jquery.com/ui/1.10.4/jquery-ui.js"></script>

 <script>
   $(function() {
     $( ".accordion" ).accordion();
     $(".accordion").accordion({ header: "h5", collapsible: true, active: false ,heightStyle: "content" });
   });
   </script>


</head>
<div class="accordion">
	<h5>Qu'est ce que l'authentification forte ?</h5>
	    <div>
	      <p>	Les systèmes d'authentification simple utilisent un seul facteur (en général un facteur mémoriel tel qu'un mot de passe). Le principe de l'authentification forte est d'utiliser plusieurs facteurs de nature distincte afin de rendre la tâche plus compliquée à un éventuel attaquant. Les facteurs d'authentification sont classiquement présentés comme suit :
			<ul>
			  <li>> ce que l'entité connaît (un mot ou une phrase de passe)</li>
			  <li>> ce que l'entité détient (une clé USB, une carte à puce, un smartphone, etc.). Soit un élément physique appelé jeton d'authentification, authentifieur ou token</li>
			  <li>> ce que l'entité est ( pour une personne physique, empreinte digitale ou tout autre élément biométrique)</li>
			  <li>> ce que l'entité sait faire ou fait (pour une personne physique, biométrie comportementale tel que signature manuscrite, reconnaissance de la voix, etc.)</li>
			  <li>> où l'entité se trouve, soit un endroit d'où, à la suite d'une identification et authentification réussie, elle est autorisée (accéder à un système logique d'un endroit prescrit)</li>
			</ul>
			Dans la majorité des cas, l'entité est une personne physique - individu - personne morale, mais elle peut être un objet comme une application web utilisant le protocole SSL, un serveur SSH, un objet de luxe, une marchandise, un animal, etc..</p>
			<p>Source: Wikipedia</p>
	    </div>
	<h5>Qu'est ce que l'identité numérique ?</h5>
	    <div>
	      <p>	L'identité numérique peut être définie comme un lien technologique entre une entité réelle (personne, organisme ou entreprise) et des entités virtuelles (sa ou ses représentations numériques).

			Le développement et l'évolution des moyens de communication, au travers notamment de la multiplication des blogs et des réseaux sociaux, changent le rapport de l'individu à autrui. Ainsi, l'identité numérique permet l'identification de l'individu en ligne et la mise en relation de celui-ci avec l'ensemble des communautés virtuelles présentes sur le Web.</p>
	    </div>
	<h5>Identité numérique et blockchain</h5>
		<div>
		 <p>Une blockchain immuable, c'est à dire pratiquement impossible à modifier, permet d'authentifier des documents grâce aux signatures électroniques. Par exemple, un tiers de confiance peut signer une transaction dans la blockchain Bitcoin qui contient l'empreinte numérique d'une carte d'identité. En donnant accès à la clé publique correspondant à la clé privée utilisée pour la signature, le tiers de confiance permet de vérifier que cette carte d'identité a été authentifiée par lui. </p>
		</div>
</div>




