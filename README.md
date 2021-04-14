# Chattermill NLP Challenge
At Chattermill we do a lot of cool things with text. One of them is aspect analysis, where we extract 
mentioned attributes of a product from customer comments (for example **speed of delivery** for a courier service). 
This is typically a hard problem to solve. That's where you come in.

### The goal
We would like you to use your favourite classification algorithm to predict the aspects from the given feedback data. 
**The emphasis is on overall code quality** rather than fine-tuning of the algorithm for superior accuracy.

### Data
There are 2 comma-separated datasets of customer reviews, `train.csv` and `test.csv`.  Each comment in 
`train.csv` has some multilabel ground-truth combination of aspects, while `test.csv` provides no ground-truth labels.

### Expected Output
We expect your code to train a classification algorithm on `train.csv` that infers on `test.csv` and exports its 
aspect predictions to a file called `test_answers.csv`.  Everything else is for you to decide. You might want to add 
some exploratory data analysis or visualisations.

Please submit your solution (including the completed `test_answers.csv` file) via a Github repo. If that's not 
possible, a zip file.  Send the link to nlp@chattermill.io

Add a README.md file explaining your process. It can be in a format of a short blog post, report or a tutorial. 
Any cool insight you find along the way, or cool tool you use will be a bonus. **The file should contain full 
instructions on what we need to do to rerun your code.**

### Notes
* You should be able to complete the project within a few hours, not days.
* Feel free to work in whatever language / framework you are most comfortable in, but we prefer Python for ML tasks.
* Feel free to use any machine learning library like Keras, TensorFlow, PyTorch
* You are free to use word vectors or pre-trained models to complete this task if you wish, however please consider 
  your memory consumption and training times (anything that takes over an hour to train on a GPU is going to be too 
  long)
* Please focus on making the code clear and modular, rather than on the complexity of the solution. **Accuracy 
  level itself will not be a success factor as much as our understanding of what you are doing and why.**
* You may use Jupyter notebooks to code and present your solution if you prefer

### Bonus Points
* Clear, readable code
* Good naming of methods
* Being able to concisely explain what you have done and why certain decisions have been made

### Get in touch
* If something isn't clear, feel free to submit an issue to this repo or drop us an email at nlp@chattermill.io
