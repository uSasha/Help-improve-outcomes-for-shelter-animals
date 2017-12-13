## Help-improve-outcomes-for-shelter-animals
### This was a kaggle in class competition. Algorithm was fixed to random forest, and metric is oob_score.

During ML express course we arranged small in class competition.
This dataset is very interesting with a lot of things to do and this solution still could be improved.

Algorithm we should use was Random Forest and metric was it’s oob_score.

This restriction made me focus on feature engineering, which I enjoyed a lot.
I made a lot of data modification, synthesized new features based on old ones, learned how to handle categorial features and even found a way to improve my solution with external data.

My favorite part is this: I decided that size is very important for potential owner and it should inflience outcome, so I found table with breeds and it's sizes (weights) and added this data to my dataset, which lead to huge score improvement.

This is one of my favorite competitions also because here all feature really made sense and a good solution potentially could make the world a better place.

If you have time I highly recommend to try it.
You can find dataset and description here: https://www.kaggle.com/c/shelter-animal-outcomes

### Potential improvements:
- add coat type based on breed
- implement different solvers for dogs and cats
