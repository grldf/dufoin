<script>
  import Date from "./components/date.svelte";
  import Lieu from "./components/lieu.svelte";
  import Spectacle from "./components/spectacle.svelte";
</script>

<main>
  <header>
    <h1>Du foin sur les planches <br /> non officiel</h1>
    <p>
      Ce site a été fait car l'officiel du festival présente seulement des
      images et c'est pas top...Cette page est certainement pas parfaite (fait
      en 24h) mais j'espère que vous trouverez des choses pratiques et
      intéressantes.
    </p>
  </header>
  <!-- --------------------------------------------Vendredi 18 ---------------------------------------- -->
  <h2>PROGRAMME</h2>
  <div class="head">
    <Date
      day={"Vendredi"}
      numberOfDay={"18"}
      month={"Juin"}
      year={"2021 à 19H"}
    />
    <Lieu
      title="LANCEMENT DU FOIN SUR LES PLANCHES 2021 + CONCERT"
      position="Le Chapelard - la Chapelle de Madore"
      reservation={"Bah non..."}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"20H"}
      hourTitle={"Concert Laniakela chanson française"}
      underTitle={"Guitare-chant: Corentin Roffat - Basse et violoncelle: Gaëlle Hostein - Percussions: Philippe Berthelon"}
      localisation={"Le Chapelard - la Chapelle de Madore"}
      infos={"Infos: Buvette sur place"}
      price={"Gratuit"}
      presentation={"Ce groupe circuit-court du Beaujolais vert se distingue par son engagement et sa poésie. Les compositions toutes personnelles de l'auteur compositeur interprète Corentin font là toute l'originalité et la profondeur de ce groupe très prometteur."}
    />
  </div>
  <!-- --------------------------------------------samedi 19 ---------------------------------------- -->

  <div class="head">
    <Date day={"Samedi"} numberOfDay={"19"} month={"Juin"} year={"2021"} />
    <Lieu
      title="JAZZ A LA FERME"
      position="Madore et la Chapelle de Madore"
      reservation={"<a href='tel:+330625055035'>0625055035</a>"}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"11H30"}
      hourTitle={"De Brassens da Bahia au Samba français"}
      underTitle={"Bruno-Michel Abati: Voix/Guitare - Manuel Fillat: Saxophone"}
      localisation={"Au lieu dit: Les Entremains de Mardore Gîte rurale de Philippe Crouzet"}
      infos={"Infos: Buvette et petite restauration sur place"}
      price={"Au chapeau"}
      url={"https://www.youtube.com/embed/ku-rqt2GOvs"}
    />
    <Spectacle
      hour={"15H"}
      hourTitle={"Chamoun & the Afropicals"}
      underTitle={"Afro-soul jazz, reggae, world musique"}
      localisation={"A la ferme Desseigne - GAEC chez Chapelle - La Chapelle de Mardore"}
      infos={"Infos: Buvette et petite restauration sur place"}
      price={"Au chapeau"}
      url={"https://www.youtube.com/embed/PSqo0_2gVUw"}
    />
    <Spectacle
      hour={"19H"}
      hourTitle={"Gospel et  grand standards"}
      underTitle={"Chantés par Marie-Claire Boyadjian"}
      localisation={"Eglise La Chapelle de Mardore"}
      infos={"Infos: Buvette et petite restauration sur place"}
      price={"Au chapeau"}
      url={"https://www.youtube.com/embed/xx5h--cY-n0"}
    />
    <Spectacle
      hour={"20H30"}
      hourTitle={"Coktail New Orleans et repas swing"}
      underTitle={""}
      localisation={"Les terrasses du Chapelard"}
      price={"Prix 13€/10€ adhérents sur réservation"}
    />
  </div>
  <!-- --------------------------------------------Vendredi 25 ---------------------------------------- -->

  <div class="head">
    <Date
      day={"Vendredi"}
      numberOfDay={"25"}
      month={"Juin"}
      year={"2021 à 19H30"}
    />
    <Lieu
      title="LE COVID VU PAR LE THEATRE"
      position="MJC d'Amplepuis"
      reservation={"<a href='tel:+330625055035'>0625055035</a>"}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"19H30"}
      hourTitle={"Covid au Château"}
      underTitle={"3 zooms théatraux - Création atelier théâtre adulte"}
      localisation={"MJC d'Amplepuis"}
      price={"Prix 5€ pour la soirée sur réservation"}
      infos={"Infos: Buvette sur place"}
      presentation={"L'action se passe en 2020/2021 à Amplepuis dans le beaujolais Vert en période de pandémie. Les 3 soeurs De Montibert gèrent difficilement le patrimoine de leur château en péril. Le papa à l'Ehpad, Héloïse tient en acrobate la gestion d'un batiment historique qui s'écroule malgré l'aide des anciens domestiques Clara et Gégé.<br/> Les deux autres soeursVéra et Graziella vivent égoistement et désintéressées de leur patrimoine aux USA et à Dubaï. La mort du père pour raison Covid et la mission patrimoine de Stéphan Vern vont révolutionner l'avenir de cette famille divisée et de leur région...<br/>\"Covid au château\" se jouera en entier en octobre 2021"}
    />
    <Spectacle
      hour={"20H"}
      hourTitle={"Après...le monde"}
      underTitle={"Création Théâtre universitaire Lyon 1, théâtre D'Ouble"}
      localisation={"MJC d'Amplepuis"}
      price={"Prix 5€ pour la soirée sur réservation"}
      infos={"Infos: Buvette sur place"}
      presentation={'Une communauté de jeunes reclus dans une étrange prison...Ce sont des mythos, excentrique, psychopathes?<br/>Une prêtresse "big sister BIGDATARONA" les surveille sur écran!<br />La syndémie mondiale fait tomber le 4ème mur de cette prison mentale...<br />Vont-ils pouvoir ré-inventer un Après...Monde?<br />Un questionnement urgent sur notre monde d\'après!'}
    />
    <Spectacle
      hour={"21H30 à 22H15"}
      hourTitle={"Rencontre avec les artistes"}
      underTitle={"Théâtre universitaire Lyon 1, théâtre D'Ouble"}
      localisation={"MJC d'Amplepuis"}
      price={"Prix 5€ pour la soirée sur réservation"}
      infos={"Infos: Buvette sur place"}
    />
  </div>
  <!-- --------------------------------------------Samedi 26 ---------------------------------------- -->

  <div class="head">
    <Date day={"Samedi"} numberOfDay={"26"} month={"Juin"} year={"2021"} />
    <Lieu
      title="La FÊTE AU VILLAGE"
      position="La Chapelle de Mardore - Thizy-Les-Bourgs"
      reservation={"Assiette festival sur réservation <a href='tel:+330625055035'>0625055035</a>"}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"11H"}
      hourTitle={"Recuptou laploubelle"}
      underTitle={"Compagnie Rien est perdu"}
      localisation={"École (spectacle famille)"}
      price={"Prix 2€"}
      infos={""}
      presentation={"Théâtre d'objets sonores (40 min)<br /> Conception et interprétation: Frank Cavet<br />Marionnettes et humour de 6 à 1000 ans. Une fable verte pour recycler le plastique. Une histoire qui sensibilise les enfants au recyclage de nos déchets plastique et les adultes pourront réfléchir sur le moins polluer."}
    />
    <Spectacle
      hour={"12H15"}
      hourTitle={"Concert : Le groupe Frère"}
      underTitle={"Chanson française"}
      localisation={"Le Chapelard (apéro concert)"}
      price={"Au chapeau"}
      infos={""}
      presentation={'Des textes qui ont du flair et des musiques d\'une nouvelle ère (sons urbains, chansons, pop, électro, hip hop, latino...) Ces 2 jeunes artistes touchent à tout parlent de leur époque comme leur derniier morceau "Les treize confinement"...'}
      url={"https://www.youtube.com/embed/hJCrOz_pjfw"}
    />
    <Spectacle
      hour={"13H à 14H30"}
      hourTitle={"Assiette festival"}
      underTitle={"Salé - Sucré"}
      localisation={"Le Chapelard"}
      price={"10€"}
      infos={"Sur réservation"}
      presentation={""}
    />
    <Spectacle
      hour={"14H à 15H"}
      hourTitle={"Podcats sonore Frères"}
      underTitle={"Documentaire radio"}
      localisation={"École"}
      price={"Gratuit"}
      infos={"Salle de classe d'école"}
      presentation={"David et Rémi sont jumeaux et infirmes moteur cérébral. Ils ne devaient jamais parler ni marcher. À 34 ans, ils nous parlent dans un documentaire réalisé par leur frère Nicolas François et sa compagne Aurélia Balboni.<br />Frère à reçu une mention méritée de jury des Phonugria Nova Awards 2020. Un témoignage magnifique, dans l'intimité d'une famille qui défie les lois de l'ordinaire. Le couple raconte...<br /> À réécouter en podcast: \"Frères\", le combat magnifique d'une famille face à l'infirmité moteur cérébrale (télérama.fr)<br />Rencontre avec David et Rémi et leurs parents."}
    />
    <Spectacle
      hour={"14H à 15H"}
      hourTitle={"Atelier manga enfants - jeux en bois d'antan"}
      underTitle={"en parallèle"}
      localisation={"École"}
      price={"Gratuit"}
      infos={"Cour d'école"}
      presentation={"Animations"}
    />
    <Spectacle
      hour={"15H à 15H30"}
      hourTitle={"Jeux de piste: la route des vins"}
      underTitle={"Bistrot culturel"}
      localisation={"Le Chapelard"}
      price={"Gratuit"}
      infos={""}
      presentation={"Programmé depuis 2012 dans la meilleure des ambiances des repas-spectacles très prisés. Au 50ème spectacles, certains farfelus de Courant d'Art ont eu la bonne idée d'enterrer dans le village 50 bouteilles offertes par les adhérents et proches.<br />Par un jeu d'énigmes, vous allez découvrir en 30 minutes et 500 mètres de marche ce village si particulier La Chapelle De Mardore et ces 50 bouiteilles à boirte tout le week-end de façon partagée..."}
    />
    <Spectacle
      hour={"15H30 à 18H"}
      hourTitle={"Animations de rue dans tous le village"}
      underTitle={"Les Zurbamateurs / La fleur des mots / Les bêtes de foires "}
      localisation={"La rue"}
      price={"Gratuit et au chapeau"}
      infos={""}
      presentation={"Les Zurbamateurs: batucada (percussion et danse)<br />La fleur des mots: orgue de barbarie<br />Les bêtes de foire: clowns (Collectif d'êtr'acteur)"}
      url={"https://www.youtube.com/embed/8DbnAssy0U8"}
    />
    <Spectacle
      hour={"18H à 20H"}
      hourTitle={"Les folk furieuses"}
      underTitle={"Initiation au bal masqué & folk distancié"}
      localisation={"Place du village"}
      price={"Gratuit"}
      infos={"Petite restauration"}
      presentation={"Les folk furieuses: musique trd relookée. Deux filles, deux accordéons diatoniques, deux voix, quatre mains. deux douces tarées droguées dure à la musique trad! (source leur Facebook)  "}
      url={"https://www.youtube.com/embed/F3YP4y4NPNQ"}
    />
  </div>
  <!-- --------------------------------------------Mardi 29 ---------------------------------------- -->

  <div class="head">
    <Date day={"Mardi"} numberOfDay={"29"} month={"Juin"} year={"2021"} />
    <Lieu
      title="PAS SAGE - Olivier Ponsot"
      position="Amplepuis"
      reservation={"<a href='tel:+330474894271'>0474894271</a>"}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"18H durée 50 minutes"}
      hourTitle={"Pas sage "}
      underTitle={"Conte jeune public à partir de 6 ans"}
      localisation={"MJC d'Amplepuis"}
      price={"Prix 6€ sur réservation"}
      infos={"Infos: Buvette"}
      presentation={"Olivier Ponsot est un conteur déjanté et décoiffé / Théâtre monté sur roulement à billes.<br /> Attention! Cet homme est dangereux: il est entré dans le conte par effraction.<br />Le début de ces histoires: il ne les connaît pas bien. La fin, il n'en est pas sûr. Et pour le milieu, il vous fait confiance...<br /><br />Il enchaîne les petites histoires puis d'un coup nous suspend et nous émeut dans un récit inattendu qu'il improvise spécialement pour son public du moment.<br /><br />Valise à la main, cheveux peignés par tous les courants d'airt du monde, ce balladin du 21ème siècle lance un nouvel art: conteur funambule sur corde vocale!"}
    />
  </div>
  <!-- --------------------------------------------Vendredi 2 Juillet ---------------------------------------- -->

  <div class="head">
    <Date day={"Vendredi"} numberOfDay={"2"} month={"Juillet"} year={"2021"} />
    <Lieu
      title="CARNETS DES SOUVENIRS"
      position="Lac des sapins (entrée digue)"
      reservation={"<a href='tel:+330625055035'>0625055035</a>"}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"19H"}
      hourTitle={"Cabaret concert"}
      underTitle={"Musique du monde"}
      localisation={"Centre équestre du lac des sapins (entrée digue)"}
      price={"Prix 10€ pour la soirée (gratuit -14 ans) sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"Joseph Pariaud en duo avec l'accordéoniste Claire Mével chantent les terres d'Argentine à celles des balkans, ses influences music-hall d'Yves Montand à Serge Reggiani"}
      url={"https://www.youtube.com/embed/CAboQ9iDulM"}
    />
    <Spectacle
      hour={"20H30"}
      hourTitle={"Le rapport de brodeck"}
      underTitle={"Théâtre"}
      localisation={"Centre équestre du lac des sapins (entrée digue)"}
      price={"Prix 10€ pour la soirée (gratuit -14 ans) sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"Le lendemain de la seconde guerre mondiale. L'Étranger, l'Autre, l'Anderer est assassiné par les hommes du village. Brodeck arrive dans l'auberge juste après le meurtre. On le charge de raconter, d'écrire un rapport, de rendre compréhensible voire admissible cet acte collectif de barbarie... Comment accepter l'Étranger?<br />Une question d'hier et encore d'aujourd'hui..."}
    />
    <Spectacle
      hour={"22H"}
      hourTitle={"Rencontre avec les artistes"}
      underTitle={"Théâtre"}
      localisation={"Centre équestre du lac des sapins (entrée digue)"}
      price={"Prix 10€ pour la soirée (gratuit -14 ans) sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"Rencontre"}
    />
  </div>
  <!-- --------------------------------------------Samedi 3 Juillet ---------------------------------------- -->

  <div class="head">
    <Date day={"Samedi"} numberOfDay={"3"} month={"Juillet"} year={"2021"} />
    <Lieu
      title="DU FOIN AU LAC"
      position="Centre équestre du lac des sapins"
      reservation={"<a href='tel:+330625055035'>0625055035</a>"}
    />
  </div>
  <div class="day">
    <Spectacle
      hour={"15H"}
      hourTitle={"FCL (chanson verte"}
      underTitle={"chanson française"}
      localisation={"Centre équestre du lac des sapins (entrée côté digue)"}
      price={"Prix 4 spectacles 15€ / Didier Super 10€ sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"Un groupe circuit court et écologique dans la lignée Fréro Delavega ou Tryo."}
    />
    <Spectacle
      hour={"16H30"}
      hourTitle={"Squalid"}
      underTitle={"Rap"}
      localisation={"Centre équestre du lac des sapins (entrée côté digue)"}
      price={"Prix 4 spectacles 15€ / Didier Super 10€ sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"4 rappeurs et un beatmaker lyonnais entre kickage et autotune, anglais et français avec du talent à revendre (Oorun, Hito, John Doe mais aussi Arona)"}
      url={"https://www.youtube.com/embed/1Qo_G91KC2g"}
    />
    <Spectacle
      hour={"18H"}
      hourTitle={"Red Session"}
      underTitle={"Power rock"}
      localisation={"Centre équestre du lac des sapins (entrée côté digue)"}
      price={"Prix 4 spectacles 15€ / Didier Super 10€ sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"Références Nirvana, Royal Blood, Radiohead, Rage Against the Machine, Nothing but Thieves, Green Day et sont agrémentés d'influences métal, gospel, rock altenatif, punk, blues, rock progressif et électro. Tout est dit avec leurs nouvelles compos croonés par leur chanteuse Maud."}
      url={"https://www.youtube.com/embed/EMn6Fn9Esmo"}
    />
    <Spectacle
      hour={"21H"}
      hourTitle={"Didier Super"}
      underTitle={"Humour punk"}
      localisation={"Centre équestre du lac des sapins (entrée côté digue)"}
      price={"Prix 4 spectacles 15€ / Didier Super 10€ sur réservation"}
      infos={"Infos: Buvette et petite restauration"}
      presentation={"Didier Super la tête d'affiche imprésentable à vos parents."}
      url={"https://www.youtube.com/embed/PNN-4VvVafY"}
    />
    <Spectacle
      hour={"Carte avec les différents lieux"}
      hourTitle={"Je ne certifie rien"}
      underTitle={"Si vous vous perdez profitez des paysages..."}
      localisation={"Un peu partout dans le coin..."}
      price={""}
      infos={""}
      presentation={"Il manque la ferme Desseigne - GAEC chez Chapelle - La Chapelle de Mardore"}
      url={"https://www.google.com/maps/d/u/1/embed?mid=1Unq1Lu3gvkniJkEEe0i6eiH7RHP8Tm99"}
    />
  </div>
  <div class="day" />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
    background-image: url("./background.jpg");
  }
  .day {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    grid-auto-flow: dense;
    gap: 25px;
  }
  .head, header {
    text-align: center;
    background-color: rgba(25, 25, 25, 0.8);
    padding: 5px 0;
    margin: 10px 0;
    border: 1px solid rgb(87%, 87%, 67%);
  }
  h1 {
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
