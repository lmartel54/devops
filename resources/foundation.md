<div id="header" align="center">
  <img src="" width="250"/>
</div>
<h3>Les fondements</h3>
<ul>
	<li><b><a href="./agile.md">AGILE</a></b>, <b><a href="./lean.md">LEAN</b></a> (gestion organisationelle), <b><a href="./itsm.md">ITSM</a></b> (IT Service Management) </li>
	<br>
	<li><b>CALMS</b></li>
	<br>
	<p>Framework (initié par <b>Jez Humble</b>) permettant d'évaluer la capacité d'une entreprise à adopter les processus DevOps</p>
	<ul>
		<li><b>C</b>ulture: Partage de la vision et des responsabilités entre les différents acteurs</li>
		<li><b>A</b>utomatisation: Elimine les tâches manuelles répétitives, exploite des processus reproductibles et crée des systèmes fiables</li>
		<li><b>L</b>ean: Elimine les activités à faible valeur ajoutée</li>
		<li><b>M</b>esure:</li>
		<li><b>S</b>haring: Partage d'informations</li>
	</ul>
	<br>
	<li><b>THREE WAYS</b></li>
	<br>
	<p>Rédigé par <b>Gene Kim</b> dans le livre "The Phoenix Project", décrit une façon de fournir de la valeur à un rythme plus rapide</p>
	<ul>
		<li><u><b>Flux</b></u>: Comprendre et améliorer le flux de travail</li>
		</p>
		<p><i>La première voix met l'accent sur la pensée systémique, l'optimisation du processus métier, sa rationalisation et sa fiabilité</i></p>
		<div>
			<table>
				  <tr>
					  <td><b>Continuous integration</b> (CI)</td>
					  <td>Méthode consistant à intègrer régulièrement les modifications à un référentiel centralisé, à partir duquel sont déclenchées automatiquement les étapes [build] et [test] visant à contrôler : la qualité, la conformité, la non régression...</td>
				  </tr>
				  <tr>
					  <td><b>Continuous Delivery</b> (CD)</td>
					  <td>Acceptation -> <b>Trigger</b> (action manuelle) -> Production</td>
				  </tr>
				  <tr>
					  <td><b>Continuous Deployment</b> (CD)</td>
					  <td>Acceptation -> Production</td>
				  </tr>
				  <tr>
					  <td><b>Lean</b></td>
					  <td>Philosophie qui vise à <b>réduire le gaspillage</b> et améliorer en continue les processus</td>
				  </tr>
				  <tr>
					  <td><b>VSM</b><br>(Value Stream Mapping)</td>
					  <td>
						<b>Cartographie des flux</b> (production/information) visant à identifier:
						<ul>
							<li>les opérations sans valeur ajoutée afin de les supprimer ou de les réduire</li>
							<li>les opportunités d’amélioration</li>
						</ul>	
					  </td>
				  </tr>
				  <tr>
					  <td><b>Kanban</b></td>
					  <td>
						<b>Méthode</b> inventée en 1950 par Taiichi Ohno chez Toyata <b>visant à améliorer le flux de travail</b>:
						<ul>
							<li>flux tendu: <b>tiré par la demande</b>, et non poussée à partir des prévisions</li>
							<li><b>réduction</b> de l'espace, des stocks et du <b>WIP</b> (Work in Progress)</li>
							<li><b>visualisation du travail</b> : dashboard permettant de suivre l'état d'avancement des tâches à accomplir [REQUESTED, IN_PROGRESS, DONE]</li>
							<li><b>mesure la vélocité</b> de l'équipe (quantité de travail par itération)</li>
						</ul>	
					  </td>					  
				  </tr>
				  <tr>
					  <td><b>ChatOps</b></td>
					  <td>Approche permettant la collaboration des opérations techniques et commerciales via un groupe de discution</td>
				  </tr>	  
				  <tr>
					  <td><b>DevSecOps</b></td>
					  <td>Etat d'esprit qui prône la responsabilité partagée de la sécurité d'un système</td>
				  </tr>	  
				  <tr>
					  <td><b>Théorie des Contraintes</b><br>(TOC)</td>
					  <td>Initié par Eliyahu M. Goldratt dans le livre "The Goal" en 1984</td>
				  </tr>  
			</table>
		</div>
		<li><b>Feedback</b>: Créer des boucles de feedback</li>
		</p>
		<p><i>La deuxième voix met l'accent sur l'amélioration continue</i></p>
		<div>
			<table>
				  <tr>
					  <td><b>Fail Fast</b></td>
					  <td>Méthode d'apprentissage par l'échec</td>
				  </tr>
				  <tr>
					  <td><b>Tests automatisés</b></td>
				  	  <td>
					    	<ul>
							<li><b>Fonctionnels</b> (vérifier la conformité // cahier des charges)</li>
							<ul>
								<li>Tests unitaires</li>
								<li>Tests d'intégration</li>
								<li>Tests du système (homologation)</li>
								<li>Tests d'acceptation (recette)</li>
								<li>Tests IHM</li>
								<li>Tests de non-régression</li>
							</ul>
							<li><b>NON fonctionnels</b></li>
							<ul>
								<li>Tests de performance</li>
								<li>Tests de charge</li>
								<li>Tests de résistance</li>
								<li>Tests de volume</li>
								<li>Tests de sécurité</li>
								<li>Tests d'installation</li>
								<li>Tests de récupération</li>
							</ul>
						</ul>	
					  </td>
				  </tr>
				  <tr>
					  <td><b>Revue par les pairs des changements de production</b></td>
					  <td>???</td>
				  </tr>
				  <tr>
					  <td><b>Tableaux de bord</b></td>
					  <td>???</td>
				  </tr>	
				  <tr>
					  <td><b>Monitoring</b></td>
					  <td>???</td>
				  </tr>
				  <tr>
					  <td><b>Logs</b></td>
					  <td>???</td>
				  </tr>	
				  <tr>
					  <td><b>Indicateurs des processus</b></td>
					  <td>???</td>
				  </tr>	
				  <tr>
					  <td><b>Post-Mortem</b></td>
					  <td>???</td>
				  </tr>	
				  <tr>
					  <td><b>Rotation d'astreinte partagée</b></td>
					  <td>Partage d'informations entre les pilotes d'exploitation</td>
				  </tr>	
				  <tr>
					  <td><b>Données</b></td>
					  <td>gestion des changements, des incidents, des problèmes et des connaissances</td>
				  </tr>	
			</table>
		</div>
		<li><b>Expérimentation et apprentissage continus</b></li>
		</p>
		<p><i>La troisième voix met l'accent sur la culture et le comportement pour atteindre la maîtrise</i></p>
		<div>
			<table>
				  <tr>
					  <td><b>PDCA</b><br>(Deming Cycle)</td>
					  <td>
						Méthodologie itérative permettant d'atteindre la condition cible
						<ul>
							<li><b>Plan</b>: définir les objectifs</li>
							<li><b>Do</b>: exécuter</li>
							<li><b>Check</b>: vérifier les résultats obtenus</li>
							<li><b>Act</b>: évaluer puis réessayez</li>
						</ul>
					  </td>
				  </tr>
				  <tr>
					  <td><b>Improvement Kata</b></td>
				  	  <td>
						Façon structurée de créer une culture d'apprentissage  
					    	<ol type="1">
							<li>Comprendre la vision ou l’orientation à long terme</li>
							<li>Analyser l’existant et savoir l'évaluer (Métrics)</li>
						  	<li>Définir un objectif d’amélioration</li>
							<li><b>PDCA*</b> : Expérimenter vers l'objectif</li>
						</ol>	
					  </td>
				  </tr>
				  <tr>
					  <td><b>Ignite</b></td>
					  <td>Session de 5 minutes sur des sujets spécifiques</td>	  
				  </tr>	  
				  <tr>
					  <td><b>Hackatons</b></td>
					  <td>???</td>
				  </tr>
				  <tr>
					  <td><b>Dojos</b></td>
					  <td>Endroit où les membres de l'équipe DevOps se rendent pour une formation pratique (initié par Target)</td>
				  </tr>
				  <tr>
					  <td><b>Garages</b> (IBM)</td>
					  <td>Aide les entreprises à les transformer en produits minimum viables (MVP)</td>
				  </tr>
				  <tr>
					  <td><b>Lofts</b> (Amazon)</td>
					  <td>Tout ce dont vous avez besoin pour démarrer et développer votre startup avec AWS</td>
				  </tr>
				  <tr>
					  <td><b>Chaos Engineering</b></td>
					  <td>
					    	<ul>
							<li><b>Design for failure</b> (DFF) est la capacité d’un système à résister aux pannes</li>
							<table>
								  <tr>
									  <td>Timeout</td>
									  <td>Gérer les délais d'attente</td>
								  </tr>
								  <tr>
									  <td>Retry</td>
									  <td>Gérer l'indisponibilité</td>
								  </tr>
								  <tr>
									  <td>Fallback</td>
									  <td>Assurer une réponse, même "dégradée"</td>
								  </tr>
								  <tr>
									  <td>Circuit Breaker</td>
									  <td>Isoler les défaillances</td>
								  </tr> 
								  <tr>
									  <td>Bulkhead</td>
									  <td>Eviter l'effet domino</td>
								  </tr> 
								  <tr>
									  <td>BackPressure<br>Rate Limiter</td>
									  <td>Gérer la charge</td>
								  </tr> 
							</table>
							<li><b>Simian Army</b> est suite d’outils développés par <b>Netflix</b> pour tester la fiabilité, la sécurité ou la résilience de ses infrastructures (AWS)</li>
							<table>
								  <tr>
									  <td>Choas Monkey</td>
									  <td>1er logiciel conçu en 2011<br>capable de mettre délibérément hors service des instances dans l’environnement de production</td>
								  </tr>
								  <tr>
									  <td>Chaos Gorilla</td>
									  <td>Logiciel capable de faire tomber une zone complète de disponibilité</td>
								  </tr>
								  <tr>
									  <td>Chaos Kong</td>
									  <td>Logiciel capable de faire tomber une région complète</td>
								  </tr>
								  <tr>
									  <td>Latency Monkey</td>
									  <td>Gestion de la perte de performance (voir de l'indisponibilité) d'un composant externe</td>
								  </tr> 
								  <tr>
									  <td>Doctor Monkey</td>
									  <td>Gestion des instances présentant des risques de santé</td>
								  </tr> 
								  <tr>
									  <td>Janitor Monkey</td>
									  <td>Gestion des instances non utilisées</td>
								  </tr> 
								  <tr>
									  <td>Conformity Monkey</td>
									  <td>Gestion des instances non conformes</td>
								  </tr> 	
								  <tr>
									  <td>Security Monkey</td>
									  <td>Gestion des instances qui présentent des vulnérabilités</td>
								  </tr> 
								  <tr>
									  <td>10–18 Monkey</td>
									  <td>Gestion des instances qui présentent des problèmes de localisation ou de langage (l10n-i18n)</td>
								  </tr> 
							</table>
						</ul>
					  </td>		  
				  </tr>
			</table>
		</div>
	</ul>	
</ul>
