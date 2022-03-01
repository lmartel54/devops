<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
<div>
	<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
</div>
#Comment définir la "culture" DEVOPS ?

En utilisant le cercle d'or, méthode popularisée par Simon Sinek (visant à améliorer la stratégie de communication des entreprises)

	+ WHY : définir un modèle organisationnel visant à aligner les objectifs Business avec sur ceux de l'IT
	+ HOW : en augmentant la chaîne de valeur : Personnes / Processus / Automatisation
	+ WHAT : en valorisant les méthodologies, framework et outils prônant la collaboration et l'amélioration continue

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
===================================> page 58 the three ways
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx 

Historique:

	2003 : SRE (Site Reliability Engineering) : poste d'ingénieur créé par Google pour travailler sur la robustesse de l'infrastructure (resilience) et la haute disponibilité des services
			=> basée sur une collaboration plus étroite entre ingénieurs de production et équipe de développement

	2007 : Patrick Debois initie le terme [DEV-OPS]              XXXXXX en travaillant sur projet de "testing" (mur ????) XXXXX
		   Andrew Shafer et Lee Thompson initie le terme [Mur de la confusion]

	2008 : Andrew Shafer lance l'idée d'une "infrastructure Agile" (soutenu par Patrick Debois) 
		   => donne naissance à un groupe de discution Google [Agile System Administration](https://groups.google.com/g/agile-system-administration)

	06/2009 : John Allspaw et Paul Hammond (Flickr) relance l'idée lors du Velocity O'Reilly durant une conférence : "10+ Deploys per Day : Dev and Ops Cooperation at Flickr"
		   
	10/2009 : Patrick Debois initie les [DevOps Days](https://devopsdays.org), suite à un Twitte de Paul Nasser
		   => donne naissance au hashtag #DevOps sur Twitter
		   
Fondements:

	Ce qu'il n'est pas :  [5 Things DevOps is NOT](http://devops.com/2016/03/17/what-devops-is-not/)

	DevOps est basé sur un CBOK (Collective Body of Knowledge) : référentiel de connaissances partagées et collectives :
	
		+ Des conférence(s)
		
			+ [DevOps Days](https://devopsdays.org) initié par Patrick Debois en 2009
			+ [Devops Enterprise Summit](https://events.itrevolution.com) fondé par Gene Kim en 2014
			+ ...
			
		+ Des rapport(s)
		
			+ Accelerate State of DevOps : rapport annuel produit par l’équipe DORA (DevOps Research & Assessment) de Google Cloud
			    + évaluer la vélocité
					+ Deployment Frequency: fréquence à laquelle une organisation réussit à mettre en production
					+ Lead Time for Changes: Le temps qu'il faut à un commit pour passer en production
				+ évaluer la stabilité
					+ Change Failure Rate : Le pourcentage de déploiements provoquant un échec en production
				    + Time to Restore Service (MTTR) : Combien de temps il faut à une organisation pour se remettre d'une panne de production
					
			+ The State of DevOps Report : rapport annuel produit par Puppet
					
			+ Upskilling IT : rapport annuel produit par le DevOps Institute 
				+ évaluer les compétences 			
		
		+ Des ouvrage(s) de référence
		
			+ 2013 : The Phoenix Project (Gene Kim, Kevin Behr, George Spafford)
			
				+ Three ways : (initié par Gene Kim) décrit une façon de fournir de la valeur à un rythme plus rapide
								=> C'est une question d'attitude, de comportement et de culture (ABC des TIC)
				
					+ Flux : Comprendre et améliorer le flux de travail
							=> La première met l'accent sur la pensée systémique, l'optimisation du processus métier, sa rationalisation et sa fiabilité
							
							LEAN ???? ==> amélioration continue des processus de production
							
								Intégration continue,
								Livraison continue,
								Déploiement continu,
								
								+ VSM (Value Stream Mapping): Cartographie des flux (production/information) visant à identifier :
										+ les opérations sans valeur ajoutée afin de les supprimer ou de les réduire
										+ les opportunités d’amélioration
								
								+ Kanban : méthode inventée en 1950 par Taiichi Ohno chez Toyata visant à améliorer le flux de travail 
										+ vise un flux tendu: production est tirée par la demande, non poussée à partir des prévisions
										+ pour réduire : l'espace, les stocks et le WIP (Work in Progress)
										+ en utilisant un dashboard : pour prioriser et suivre l'état d'avancement des tâches à accomplir [REQUESTED, IN_PROGRESS, DONE]
								
								+ Théorie des Contraintes (TOC) initié par Eliyahu M. Goldratt dans le livre "The Goal" en 1984
					
					+ Feedback : Créer des boucles de feedback permettant une amélioration continue 
					
							+ Fail Fast : méthode d'apprentissage par l'échec
							
							+ Tests automatisés
							
								+ fonctionnels (ont pour but de vérifier la conformité par rapport au cahier des charges)
								
									• Tests unitaires
									• Tests d'intégration
									• Tests du système (homologation)
									• Tests d'acceptation (recette)
									• Tests IHM
									• Tests de non-régression
								
								+ non fonctionnels
								
									• Tests de performance
									• Tests de charge
									• Tests de résistance
									• Tests de volume
									• Tests de sécurité
									• Tests d'installation
									• Tests de récupération
									
							Revue par les pairs des changements de production,
							Pratiques de surveillance et de notification,
							Tableaux de bord
							Monitoring
							Logs
							Mesures/Indicateurs de processus
							Autopsie,
							Rotation d'astreinte partagée,
							Données de gestion des changements, des incidents, des problèmes et des connaissances (créer et intégrer des connaissances si nécessaire).
					
					+ Expérimentation et apprentissage continus
					
							+ PDCA (Deming Cycle)
							
							+ Improvement Kata : 
							
								+ Définir la direction (l'objectif "idéal" à atteindre)
								+ Comprendre la situation actuelle et savoir l'évaluer (métrics)
								+ Etablir le prochain état cible
								+ PDCA : méthodologie itérative permettant d'atteindre la condition cible
									+ Plan : définir les objectifs
									+ Do : exécuter
									+ Check : vérifier les résultats obtenus
									+ Act : évaluer puis réessayez
							
							+ Hackatons
							
							+ Chaos Engineering:
								
								+ Design for failure : (DFF) est la capacité d’un système à résister aux pannes
									+ Timeout (gérer les délais d'attente)
									+ Retry (gérer l'indisponibilité)
									+ Fallback (assurer une réponse "dégradée")
									+ Circuit Breaker (isoler les défaillances)
									+ Bulkhead (éviter l'effet domino)
									+ BackPressure & Rate Limiter (gérer la charge)
								
								+ Simian Army : suite d’outils développés par Netflix pour tester la fiabilité, la sécurité ou la résilience de ses infrastructures (AWS)
								
									+ Choas Monkey : 1er logiciel conçu en 2011 capable de mettre délibérément hors service des instances dans l’environnement de production
									+ Chaos Gorilla : logiciel capable de faire tomber une zone complète de disponibilité
									+ Chaos Kong : logiciel capable de faire tomber une région complète
									+ Latency Monkey : gestion de la perte de performance (voir de l'indisponibilité) d'un composant externe
									+ Doctor Monkey : gestion des instances présentant des risques de santé
									+ Janitor Monkey : gestion des instances non utilisées
									+ Conformity Monkey : gestion des instances non conformes
									+ Security Monkey : gestion des instances qui présentent des vulnérabilités
									+ 10–18 Monkey : gestion des instances qui présentent des problèmes de localisation ou de langage (l10n-i18n)
			
			+ 2016 : The Devops Handbook (Gene Kim, Jez Humble, Patrick Debois, John Willis)
			
				+ CALMS est un framework (initié par Jez Humble) permettant d'évaluer la capacité d'une entreprise à adopter les processus DevOps
				
					+ Culture : Partage de la vision et des responsabilités entre les différents acteurs
					+ Automatisation : d'éliminer les tâches manuelles répétitives, exploite des processus reproductibles et crée des systèmes fiables
					+ Lean : 
					+ Mesure : 
					+ Sharing : Partage d'informations
			
			+ ...
	    

	
	
	

	
Module 2	Les principes fondamentaux de DevOps
Module 3	Les principales pratiques de DevOps
Module 4	Frameworks business et technologique
Module 5	Culture, comportements et modèles opérationnels
Module 6	Automatisation et architecture des toolchains DevOps
Module 7	Mesures, indicateurs et reporting
Module 8	Partage, observation et évolution

AGILE
SCRUM : flux de travail des développeurs
Lean : pour augmenter l’efficacité de l’IT 
ITIL:  pour la gestion des services 
Gestion du changement organisationnel pour la culture
CI/CD : outils, les technologies et l'automatisation
ITSM

========= IT =============== 


    google treends -> courbe d'interet (taux d'audience)
