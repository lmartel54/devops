
<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<h3>Ma définition du DevOps ?</h3>
<p>J'utiliserais le <b>cercle d'or</b> (méthode popularisée par <b>Simon Sinek</b>, visant à améliorer la stratégie de communication des entreprises)</p>
<div>
	<table>
		  <tr>
			  <td><b>WHY</b></td>
			  <td>Définir un modèle organisationnel visant à aligner les objectifs Business avec sur ceux de l'IT</td>
		  </tr>
		  <tr>
			  <td><b>HOW</b></td>
			  <td>En augmentant la chaîne de valeur : Personnes / Processus / Automatisation</td>
		  </tr>  
		  <tr>
			  <td><b>WHAT</b></td>
			  <td>En valorisant les méthodologies, framework et outils prônant la collaboration et l'amélioration continue</td>
		  </tr>  
	</table>
</div>

<h3>Historique</h3>
<div>
	<table>
		  <tr>
		    <td>2003</td>
			  <td><b>SRE (Site Reliability Engineering)</b> : Poste d'ingénieur créé par Google pour travailler sur la robustesse de l'infrastructure et la haute disponibilité des services. Fondé sur l'idée d'une collaboration plus étroite entre ingénieurs de production et équipe de développement</td>
		  </tr>
		  <tr>
		    <td>2007</td>
		    <td>
			    <ul>
				    <li><b>Patrick Debois</b> initie le terme : DEV-OPS</li>
				    <li><b>Andrew Shafer et Lee Thompson</b> initie le terme : Mur de la confusion</li>
			    </ul>
		    </td>
		  </tr>
		  <tr>
		    <td>2008</td>
	 	    <td><b>Andrew Shafer</b> lance l'idée d'une "Infrastructure Agile" (soutenu par <b>Patrick Debois</b>) ce qui
			donne naissance au groupe de discution Google : <a href="https://groups.google.com/g/agile-system-administration">Agile System Administration</a>    		    
		    </td>
		  </tr>
		  <tr>
		    <td>06/2009</td>
	 	    <td><b>John Allspaw et Paul Hammond</b> relance l'idée lors d'une conférence au Velocity O'Reilly : "10+ Deploys per Day : Dev and Ops Cooperation at Flickr"	    
		    </td>
		  </tr>
		  <tr>
		    <td>10/2009</td>
		    <td><b>Patrick Debois</b> créé les <a href="https://devopsdays.org">DevOps Days</a> et donne naissance au hashtag #DevOps sur Twitter, ce qui légitime le terme
		    </td>
		  </tr>			
	</table>
</div>
		   
<h3>Fondements</h3>

<p><a href="http://devops.com/2016/03/17/what-devops-is-not/">5 Things DevOps is NOT !</a></p>
<p>
	DevOps est basé sur un <b>CBOK</b> (Collective Body of Knowledge) : référentiel de connaissances partagées et collectives
	<ul>
		<li><b>Conférences</b></li>
			<table>
				  <tr>
					  <td><a href="https://devopsdays.org">DevOps Days</a></td>
					  <td>fondé par Patrick Debois en 2009</td>
				  </tr>
				  <tr>
					  <td><a href="https://events.itrevolution.com">Devops Enterprise Summit</a></td>
					  <td>fondé par Gene Kim en 2014</td>
				  </tr>  
			</table>
		<li><b>Rapports annuels</b></li>
			<table>
				  <tr>
					  <td>Accelerate State of DevOps</td>
					  <td>
						 Publié par l’équipe <b>DORA</b> (DevOps Research & Assessment) de <b>Google Cloud</b><br>
						 <ul>
						 <li>Indicateurs de Vélocité</li>
						 <ul>
							 <li>Deployment Frequency: Fréquence à laquelle une organisation réussit à mettre en production</li>
							 <li>Lead Time for Changes: Temps qu'il faut à un commit pour passer en production</li>
						 </ul>
						 </ul>		 
						 <ul>
						 <li>Indicateurs de Stabilité</li>
						 <ul>
							 <li>Change Failure Rate: Pourcentage de déploiements provoquant un échec en production</li>
							 <li>Time to Restore Service (MTTR): Temps nécessaire à une organisation pour se remettre d'une panne de production</li>
						 </ul>
						 </ul>	
					  </td>
				  </tr>
				  <tr>
					  <td>The State of DevOps Report</td>
					  <td>Publié par <b>Puppet</b></td>
				  </tr>
				  <tr>
					  <td>Upskilling IT</td>
					  <td>
						 Publié par le <b>DevOps Institute</b></br>
						 <ul>
						 <li>Indicateurs de Compétences</li>
						 <ul>
					  </td>
				  </tr>
			</table>
		<li><b>Ouvrages de référence</b></li>
			<table>
				  <tr>
					  <td>2013</td>
					  <td>The Phoenix Project</td>
					  <td>Gene Kim, Kevin Behr, George Spafford</td>
				  </tr>
				  <tr>
					  <td>2016</td>
					  <td>The Devops Handbook</td>
					  <td>Gene Kim, Jez Humble, Patrick Debois, John Willis</b>
				  </tr>  
			</table>
	</ul>	
</p>	
			
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
