# DeepLearningProject_CineFlow
This is a movie recommendation system

# CineFlow: Your Movie Recommendation System
La version française est ci-dessous (après la version anglaise)

## Description

CineFlow is a web application that offers personalized movie recommendations based on various search criteria such as genre, actor, director, or title. 
Users can explore movie details like release year, director, main actors, and a brief summary.

## Main Features

- Search by Genre: Explore movies by selecting a specific genre.
- Search by Actor: Discover movies based on your favorite actors.
- Search by Director: Find movies directed by your favorite directors.
- Search by Title: Search for movies by their titles.

## Project Structure

- **app.py**: The main file of the Streamlit application that contains the code to load data, make predictions, and display the user interface.
- **movies2024.csv**: The dataset containing movie information.
- **articlesimilarity.npy**: The matrix of similarity between movies based on article content.
- **descriptionsimilarity.npy**: The matrix of similarity between movies based on movie descriptions.
- **requirements.txt**: The file containing all Python dependencies needed to run the application.

## Installation and Running Locally

1. Clone this GitHub repository to your local machine:
   ```bash
   git clone https://github.com/your_username/CineFlow.git
2. Install the required dependencies by running the following command:
    ```bash
    pip install -r requirements.txt
3. Set up the TMDB API key:
   - Sign up on TMDb to obtain an API key.
   - Create a .env file in the project directory.
   - Add your API key to the .env file:
      ```bash
      TMDB_API_KEY="your_api_key_here"
  - Run the application using the following command in the project directory:
     ```bash
     streamlit run app.py
  - The application will launch in your default web browser.

## How to Use the Application

1. Select the type of search: Choose from Genre, Actor, Director, or Title.
2. Perform the search based on your selection.
3. Explore the recommended movies and their details.
4. Enjoy discovering new movies!
 
## Credits
This project was developed by NGARI LENDOYE Alix.

# CineFlow: Your Movie Recommendation System
English version is above (before french version)

## Description
CineFlow est une application web qui offre des recommandations de films personnalisées basées sur divers critères de recherche tels que le genre, l'acteur, le réalisateur ou le titre. 
Les utilisateurs peuvent explorer les détails des films comme l'année de sortie, le réalisateur, les acteurs principaux et un résumé succinct.

## Principales fonctionnalités

- Recherche par genre : Explorez les films en sélectionnant un genre spécifique.
- Recherche par acteur : Découvrez des films basés sur vos acteurs préférés.
- Recherche par réalisateur : Trouvez des films réalisés par vos réalisateurs préférés.
- Recherche par titre : Recherchez des films par leur titre.

## Structure du projet

- **app.py** : Le fichier principal de l'application Streamlit qui contient le code pour charger les données, faire des prédictions et afficher l'interface utilisateur.
- **movies2024.csv** : Le jeu de données contenant des informations sur les films.
- **articlesimilarity.npy** : La matrice de similarité entre les films basée sur le contenu de l'article.
- **descriptionsimilarity.npy** : La matrice de similarité entre les films basée sur les descriptions de film.
- **requirements.txt** : Le fichier contenant toutes les dépendances Python nécessaires pour exécuter l'application.

## Installation et exécution en local

1. Clonez ce dépôt GitHub sur votre machine locale :
   ```bash
   git clone https://github.com/your_username/CineFlow.git
2. Installez les dépendances requises en exécutant la commande suivante :
   ```bash
   pip install -r requirements.txt
3. Configurez la clé API TMDB :
   - Inscrivez-vous sur TMDb pour obtenir une clé API.
   - Créez un fichier .env dans le répertoire du projet.
   - Ajoutez votre clé API au fichier .env :
     ```bash
     TMDB_API_KEY="votre_clé_api_ici"
4. Exécutez l'application en utilisant la commande suivante dans le répertoire du projet :
   ```bash
   streamlit run app.py
5. L'application se lancera dans votre navigateur web par défaut.

## Comment utiliser l'application

1. Sélectionnez le type de recherche : Choisissez parmi Genre, Acteur, Réalisateur ou Titre.
2. Effectuez la recherche en fonction de votre sélection.
3. Explorez les films recommandés et leurs détails.
4. Profitez de la découverte de nouveaux films !

## Crédits
Ce projet a été développé par NGARI LENDOYE Alix.
