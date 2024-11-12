<DOCTYPE html>
    <html lang="fr">
      <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Interpol - Chasse à l'Homme</title>
        <link
          href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap"
          rel="stylesheet"
        />
        <style>
          /* Styles de base */
          body {
              background: linear-gradient(135deg, #131212, #1a1a1a);
              color: #e0e0e0;
              font-family: 'Poppins', sans-serif;
              margin: 0;
              text-align: center;
          }
          header {
              background-color: #333;
              padding: 20px;
              display: flex;
              flex-direction: column;
              align-items: center;
          }
          h1 {
              color: #ff4c4c;
              font-size: 2.8em;
              text-transform: uppercase;
              padding: 10px 20px;
              background-color: #1a1a1a;
              border: 2px solid #ff4c4c;
              border-radius: 8px;
              display: inline-block;
              box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
          }
    
          h2 {
              font-size: 2em;
              color: #ff4c4c;
              margin: 20px 0;
              padding-bottom: 10px;
              border-bottom: 2px solid #444;
              text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
          }
          #txttitre {
              font-size: 1.5em;
              line-height: 1;
          }
          p {
              font-size: 1.1em;
              line-height: 1.6;
              max-width: 600px;
              margin: 0 auto 20px;
              color: #cfcfcf;
          }
    
          section {
              background-color: #262626;
              padding: 30px;
              border-radius: 10px;
              margin: 30px auto;
              max-width: 80%;
              box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
          }
    
         ul {
        list-style-type: none;
        padding: 0;
    }
    
    ul li {
        display: inline;
        margin: 0 15px;
    }
    
    ul li a {
        color: #cfcfcf;
        text-decoration: none;
        font-weight: 600;
        padding: 8px 10px; /* Ajoute un peu d'espace à l'intérieur de l'encadré */
        border: 1px solid #444; /* Bordure fine et discrète */
        border-radius: 4px; /* Coins légèrement arrondis */
        transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
    }
    
    ul li a:hover {
        color: #e0e0e0;
        background-color: #333333; /* Fond gris au survol */
        border-color: #666666; /* Bordure légèrement plus claire au survol */
    }
    a {
        color: #b7c9e1;
        text-decoration: none;
        font-weight: 600;
        padding: 8px 12px; /* Ajoute un peu d'espace à l'intérieur de l'encadré */
        border-radius: 4px; /* Coins légèrement arrondis */
        transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
    }
    /* Styles pour le tableau */
    /* Styles spécifiques pour le tableau */
    table {
      width: 80%;
      margin: 30px auto;
      border-collapse: collapse;
      background-color: #262626;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    
    th, td {
      padding: 15px;
      text-align: center;
      font-size: 1.1em;
      color: #cfcfcf;
      border: 1px solid #444;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.8);  /* Ombre pour améliorer la lisibilité */
    }
    
    th {
      background-color: #333;
      color: #ff4c4c;
      font-weight: bold;
      text-transform: uppercase;
      text-shadow: 3px 3px 5px rgba(1, 1, 1, 2); /* Ombre plus marquée pour les en-têtes */
    }
    
    td {
      background-color: #1a1a1a;
    }
    
    tr:hover {
      background-color: #444;
    }
    
    tr:nth-child(even) {
      background-color: #262626;
    }
    
    tr:nth-child(odd) {
      background-color: #1a1a1a;
    }
    
    td strong {
      color: #ff4c4c;
    }
    
    th:hover, td:hover {
      border-color: #666666;
    }
    
    
      img.logo {
              width: 100px;
              height: auto;
              margin-bottom: 10px;
          }
    
          .image-container {
              display: flex;
              justify-content: center;
              flex-wrap: wrap;
          }
    footer {
        background-color: #333;
        padding: 20px;
        color: #7d7c7c;
        margin-top: 40px;
        text-align: center; /* Centre le texte dans le footer */
    }
    
    footer .footer-text {
        color: #7d7c7c;
        font-size: 0.9em;
        margin-bottom: 10px;
    }
    
    footer ul.postprod {
        padding: 0;
        margin: 0 auto; /* Centre la liste */
        list-style: none;
    }
    
    footer ul.postprod li {
        color: #7d7c7c;
        font-size: 0.9em;
        margin: 10px 0; /* Espace entre chaque élément */
    }
    
          }
          .image-container img {
              border-radius: 8px;
              width: 300px;
              height: 200px;
              margin: 15px;
              transition: transform 0.3s ease, box-shadow 0.3s ease;
              box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
          }
    
          .image-container img:hover {
              transform: scale(1.05);
              box-shadow: 0 8px 16px rgba(0, 0, 0, 0.6);
          }
    
          img[src="https://i.imgur.com/tMQG1NO.png"],
          img[src="https://i.imgur.com/6HZ4DnA.png"],
          img[src="https://i.imgur.com/075HaTX.png"],
          img[src="https://i.imgur.com/lUCcZ5c.png"] {
              width: 450px;
              height: 300px;
          }
          ol.no-numbers {
        list-style-type: none;
        padding-left: 0;
    }
    
    
          #txtquentin {
              font-family: 'Courier New', Courier, monospace;
              font-size: 1.3em;
              line-height: 1.8;
              background-color: #1a1a1a;
              padding: 15px;
              border-radius: 8px;
              border: 1px solid #444;
              box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
              max-width: 80%;
              margin: 20px auto;
              text-align: left;
          }
    
          footer {
              background-color: #333;
              padding: 20px;
              color: #888888;
              margin-top: 40px;
          }
    
          footer ul {
              list-style: none;
              padding: 0;
          }
    
          footer li {
              font-size: 0.9em;
              margin: 5px 0;
          }
        </style>
      </head>
      <body>
        <header>
          <img
            src="https://i.imgur.com/yqkccv6.png"
            class="logo"
            alt="Logo Interpol"
          />
          <h1>Interpol : Chasse à l'Homme</h1>
          <div id="txttitre">
            <p>
              <strong>Recherché pour agression sur mineur avec récidives</strong>
            </p>
          </div>
        </header>
    
        <ul>
          <li><a href="#infos-sur-le-criminel">Infos sur le criminel</a></li>
          <li><a href="#premier-fait-accusation">Premier fait d'accusation</a></li>
          <li>
            <a href="#deuxieme-fait-accusation">Deuxième fait d'accusation</a>
          </li>
          <br>
          <br>
          <li><a href="#troisieme-fait-accusation">Troisième fait d'accusation</a></li>
          <li><a href="#infos-importantes">Infos importantes</a></li>
          <!-- Lien ajouté -->
        </ul>
    
        <section id="infos-sur-le-criminel">
          <a
            href="https://www.tiktok.com/@redifflive.01/video/7348605435521305889"
            target="_blank"
          >
            <img
              src="https://i.imgur.com/H7JgyKT.jpeg"
              alt="Image du suspect"
              width="300"
              height="400"
              class="img"
            />
          </a>
          <h2 id="Grotitre">Tony Mote/AstroNoxOne</h2>
          <p>
            <strong>Alias :</strong> Ouba Ouba / PédoNox / / Le père de Stevie dans
            Malcolm / PédoNox
          </p>
          <p><strong>Antécédents :</strong></p>
          <ol class="no-numbers">
            <p>
              <li>Vol avec arme</li>
              <li>agression sur mineurs avec récidive</li>
              <li>
                détention de pédo-pornographie dans le disque dur de sa ps4 slim
              </li>
            </p>
          </ol>
          <p><strong>Dernière localisation :</strong> Collège Gerard Phillipe</p>
        </section>
    
        <section id="premier-fait-accusation">
          <h2>Premier fait d'accusation</h2>
          <div class="image-container">
            <img src="https://i.imgur.com/6HZ4DnA.png" alt="Premier fait" />
          </div>
          <div id="tonyo">
            <p>
              10 avril 2024, Tony est aperçu à l'entrée du Collège Gerard Phillipe,
              exhibant ses parties génitales devant un groupe d'élèves de 5ème, un de ces élèves, victime principale nous partage son témoignage.
            </p>
          </div>
          <div class="image-container">
            <img
              src="https://i.imgur.com/tMQG1NO.png"
              alt="cobaye Unicef en sous-nutrition"
            />
          </div>
          <br />
          <div id="txtquentin">
            Il cite :
            <em
              >"Tout s'est passé très rapidement, je m'étais pencher pour refaire
              les lacet des mes</em
            ><strong> Air Max 95 Comme des Garçons</strong>
            <em>
              lorsque je vis un homme, relativement dodu,me fixer en se touchant le
              penis, il sembalit relativement petit pusiqu'il le tenait qu'avec ses
              deux doigts, il m'a régarder en disant : "Tu veux le voir mon zgeg
              hein !?" d'un ton ménacant mais séduisant.</em
            >"
          </div>
        </section>
    
        <section id="deuxieme-fait-accusation">
          <h2>Deuxième fait d'accusation</h2>
          <p>
            Dans la journée du 20 mai 2024, une vidéo est publié sur les réseaux
            sociaux, mettant en scène le présumé Tony Mote, vidant la chaussette de
            sperme de Quentin sur son visage, victime de l'incident du 10 avril, la
            vidéo a rapidement fait le tour des réseaux et nous est parvenu par
            l'intermédiaire de son cousin qui lui est sénégalais.Une enquête est
            lancée pour localiser le lieu où la vidéo à eu lieu, pour déterminer
            l'emplacement où a eu lieu la scène et pour retrouver de potentielles
            empreintes de semences appartenant au squelette en mal-nutrition
          </p>
          <div class="image-container">
            <img src="https://i.imgur.com/075HaTX.png" alt="Deuxième fait" />
          </div>
        </section>
    
        <section id="troisieme-fait-accusation">
          <h2>Troisième fait d'accusation</h2>
          <p>
            Une après midi d'été, une jeune fille lance la célèbre application Azar, une célèbre application de chat en ligne, avec la possibilité de mettre sa caméra, cette jeune fille s'amusa à aller sur cette application jusuqu'au moment où elle est tombé sur un homme <a href="#caca">voir ci-dessous</a>, un jeune adulte dénudé s'affichant fièrement avec ses tatouages tribaux, la jeune fille a eu le temps d'enregistrer la scène atroce auquelle elle a du faire face. L'homme se serait proclamé comme étant"PedoNox King Of Pointeur" , effrayé par ce qu'elle a vue, elle décida de quitter l'application et d'en parler à son grand frère appelé DarkWolf94, son identité sera garder secrette pour des raisons de confidentialité. Malheureusement l'image ne nous permettra pas de trouvé plus d'informations cependant il nous permet d'affirmer que l'assaillant n'a pas mis un termes à ses activités malsaines.</p>
            <div class="image-container">
            <img id="caca" src="https://i.imgur.com/lUCcZ5c.png"/>
            </div>
            </section>
            <h1>Statistiques Annexes</h1>
        <footer>
        <section id="statitiques-id">
        <table>
        <tr>
          <th></th>
          <th scope="col">Tony</th>
          <th scope="col">À Bourges</th>
        </tr>
        <tr>
          <th scope="row">Nombre d'agressions sexuelles sur mineurs</th>
          <td><strong>56</strong></td>
          <td><strong>37</strong></td>
        </tr>
        <tr>
          <th scope="row">Nombre d'agressions sexuelles sur majeurs</th>
          <td><strong>0</strong></td>
          <td><strong>58</strong></td>
        </tr>
      </table>
      </section>
             <div id="infos-importantes">
        <p class="footer-text">
          © 2024 - Chaque information ou donnée liée à cet individu sera récompensée de 5000$.
        </p>
        <ul class="postprod">
          <li>Directeur Artistique : The Higuma</li><br>
          <li>Post Prod : Ritchi Mote</li><br>
          <li>Rédacteur en chef : EthanRocket</li><br>
          <li>Monteur : Erwan Beauvallet</li><br>
          <li>Associés : Jordann Stieau</li>
        </ul>
      </div>
    </footer>
      </body>
    </html>
    <DOCTYPE html>
