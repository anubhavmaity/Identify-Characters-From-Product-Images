This project was done as a part of the [**Identify Characers From Product Images**](https://www.crowdanalytix.com/contests/identify-characters-from-product-images "**Identify Characers From Product Images**") competition. The competition was hosted in [**CrowdAnalytix**](https://www.crowdanalytix.com/community "**CrowdAnalyticX**"). 


### Data (Provided by CrowdAnalytix)

The data consisted of product images like t-shirts, bags, keychains, mobile covers, etc. with characters graphics. 

Training Set: 6694 images across 42 categories 
Test Set: 3727 images

The data had label inconsistency of 2-3%. Had to manually resolve the label inconsitency.

### Additional Data

As the data provided by CrowdAnalytix was not equally distributed across the 42. Some categories had fewer data comparatively to the other categories. To resolve this data insufficiency among the categories we downloaded the additional data with the help of [gi2ds](https://github.com/toffebjorkskog/ml-tools/blob/master/gi2ds.md "gi2ds")  and this [tutorial](https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/ "tutorial") created by [Andrian Rosebrook](https://www.pyimagesearch.com/author/adrian/ "Andrian Rosebrook") . 


You can download the data from [here](https://my.pcloud.com/publink/show?code=XZ2oPHkZdl53szTtWDBUeomYHofe85rC7KKV "here") (Comprises the data provided by CrowdAnalytix and the above mentioned additional data)

### Categories

The following were the 42 categories for classification.

- Angry Birds
- Baloo
- Bart simpson
- Ben
- Bulbasaur
- Charizard
- Charlie brown
- Charmender
- Chicken_little
- Cinderella
- Darth_vader
- Disney_princes
- Donald_duck
- Godzilla
- Goku
- Goofy
- Han-solo
- Harry_potter
- Hellokitty
- Itachi
- John_Cena
- Jojosiwa
- Kakashi
- Marilyn_monroe
- Mickey_mouse
- Minions
- Naruto
- Pikachu
- Pokemon
- Popeye
- Power_rangers
- R2-D2
- Roman_reigns
- Scoopy Doo
- SpongeBob SquarePants
- Squirtle
- Teenage_mutant_ninja_turtles
- Tom and Jerry
- Toy_story_characters
- Vampirina
- Vegeta
- Winnie the poo

[![Categories](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/identify-product-characters.png "Categories")](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/identify-product-characters.png "Categories")

### Confusion Matrix

[![Confusion Matrix](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/identify_characters_confusion_matrix.png "Confusion Matrix")](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/identify_characters_confusion_matrix.png "Confusion Matrix")

Pair of confused categories with minimum value of 2

[('Cinderella', 'disney_princes', 6),
 ('pokemon', 'pikachu', 6),
 ('Baloo', 'Godzilla', 5),
 ('Charlie brown', 'goofy', 5),
 ('Charlie brown', 'Bart simpson', 4),
 ('popeye', 'power_rangers', 4),
 ('Roman Reigns', 'han-solo', 3),
 ('Scoopy Doo', 'Bart simpson', 3),
 ('disney_princes', 'Baloo', 3),
 ('disney_princes', 'Cinderella', 3),
 ('donald_duck', 'goofy', 3),
 ('goofy', 'mickey_mouse', 3),
 ('popeye', 'goofy', 3),
 ('vampirina', 'jojosiwa', 3),
 ('Bart simpson', 'Charlie brown', 2),
 ('Charlie brown', 'teenage_mutant', 2),
 ('Chicken_little', 'power_rangers', 2),
 ('Godzilla', 'Tom and Jerry', 2),
 ('Godzilla', 'goofy', 2),
 ('Goku_1', 'goofy', 2),
 ('Goku_1', 'pokemon', 2),
 ('John Cena', 'Roman Reigns', 2),
 ('Tom and Jerry', 'goofy', 2),
 ('charizard', 'Goku_1', 2),
 ('disney_princes', 'Bart simpson', 2),
 ('harry_potter', 'han-solo', 2),
 ('itachi', 'Goku_1', 2),
 ('kakashi', 'power_rangers', 2),
 ('naruto', 'Goku_1', 2),
 ('naruto', 'pokemon', 2),
 ('pikachu', 'pokemon', 2),
 ('pokemon', 'angrybirds', 2),
 ('popeye', 'mickey_mouse', 2),
 ('squirtle', 'bulbasaur', 2),
 ('squirtle', 'power_rangers', 2),
 ('squirtle', 'teenage_mutant', 2),
 ('vegeta', 'goofy', 2)]
 

#### Sample Images from the confused categories
[![Misclassified Images](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/misclassified_sample_images.png "Misclassified Images")](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/misclassified_sample_images.png "Misclassified Images")

### Accuracy

The validation accuracy obtained was 90.7%

### Leaderboard Ranking 

The public leaderboard ranking: 12th with test accuracy of 89%

[![PublicLeaderboard](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/public_leaderboard.png "PublicLeaderboard")](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/public_leaderboard.png "PublicLeaderboard")

The private leaderboard ranking: 11th with test accuracy of 90%

[![Private Leaderboard](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/private_leaderboard.png "Private Leaderboard")](https://github.com/anubhavmaity/Identify-Characters-From-Product-Images/blob/master/private_leaderboard.png "Private Leaderboard")









