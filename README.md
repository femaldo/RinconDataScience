![](http://pngimg.com/uploads/pokemon_logo/pokemon_logo_PNG5.png)

# Proyecto final Data Science
#### Entrenadores:
- Carolina Lopez (カロライナ)
- Diego Luciaw (ディエゴ)
- Fabiana Torres (ファビエンヌ)
- Felipe Maldonado (フェリペ)

#### Profesor:
Luca Citta (ルウカ)

#### Líder de Gimnasio:
Octavio Lafourcade (オクタビオ)

## Introducción
El presente trabajo se realizó en el marco del proyecto final para el curso de Data Science realizado en Coderhouse. Con el mismo se propone poner en práctica lo aprendido durante la cursada y aplicar los conocimientos adquiridos para lograr un eficiente modelo de Machine Learning. Se presentará un Análisis Exploratorio de Datos (EDA),  se desarrollarán instancias como Data Acquisition, Data Wrangling, la implementación de modelos de clasificación y la optimización de los mismos mediante las herramientas trabajadas durante el curso. 

## Caso de estudio
El presente trabajo está basado en información ficticia sobre la popular y exitosa franquicia de medios Pokemon
El dataset trabajado contiene datos sobre los Pokémon registrados en todas las generaciones, con detalle de sus características, evoluciones, habilidades y estadísticas.
Mediante un análisis pertinente y posterior construcción de modelos de Machine Learning se propone predecir si un pokemon es legendario o no lo es, en base a sus características más destacables y valores estadísticos.

## Fuente
El dataset utilizado para la realización del trabajo se puede encontrar en kaggle, en el siguiente link, en su versión más actual, pokedex_(Update_04.21): https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420?select=pokedex_%28Update_05.20%29.csv. 
La información fue recopilada de las siguientes páginas:
https://pokemondb.net/ 
https://www.serebii.net/ 
La información ha sido recolectada y trabajada por Mario Tormo Romero
https://www.kaggle.com/mariotormo/

## Objetivos del proyecto

Realizar el análisis sobre las variables contenidas en el dataset elegido para posteriormente construir modelos de Machine learning que permitan predecir si un Pokemon es legendario o no lo es.

## Conclusión

En líneas generales, los resultados obtenidos con los algoritmos aplicados fueron realmente buenos, teniendo poca diferencia entre ellos. Observando más en detalle, concluimos que el modelo de mejor desempeño fue SVC bajo GridSearch para la identificación de los mejores hiperparámetros, teniendo solamente un error en la clasificación de un pokemon de características desbalanceadas. Los modelos que siguen en mejor desempeño luego de SVC, son Random Forest y XGBoost, ambos arrojaron el mismo resultado, clasificando erróneamente 1 pokemon más en comparación con el algoritmo ganador. 
