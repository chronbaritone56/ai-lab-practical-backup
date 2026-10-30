# Quick AI Lab Revision

## Topics at a glance
1. **Python Basics for AI** — This practical revises variables, lists, loops, conditions, and functions. These are the basic building blocks used in AI programs.
2. **Breadth-First Search and Depth-First Search** — BFS explores nearby nodes first using a queue. DFS follows one path as far as possible before backtracking, using a stack or recursion.
3. **A* Search Algorithm** — A* finds a low-cost path by combining the cost already travelled (g) with an estimated cost to the goal (h). The estimate is called a heuristic.
4. **Tic-Tac-Toe using Minimax** — Minimax is a decision-making algorithm for two-player games. One player tries to maximise the score while the opponent tries to minimise it.
5. **Knowledge Representation using Facts and Rules** — Knowledge representation stores information in a form a computer can use. This example uses simple facts and rules to infer a new fact.
6. **Bayes' Theorem / Simple Naive Bayes** — Bayes' theorem updates the probability of a hypothesis after seeing evidence. This simple example calculates the probability of rain given that the ground is wet, using made-up probabilities.
7. **Linear Regression and Decision Tree** — Linear regression predicts a numeric value. A decision tree learns rules that can be used for classification or prediction. This example uses scikit-learn.
8. **K-Means Clustering** — K-Means is an unsupervised learning algorithm. It groups data points into K clusters based on their similarity.
9. **Basic Natural Language Processing** — Natural Language Processing (NLP) helps computers process human language. This beginner example converts text to lowercase, removes punctuation, and counts words.
10. **Mini AI Project: Student Result Predictor** — This mini project uses a decision tree to predict a pass/fail category from study hours and attendance. The training data is tiny and only for demonstration; it should not be used for real decisions.

## Viva practice
### 1. Python Basics for AI
- **Q: What is a variable?**  
  A: A named place used to store a value.
- **Q: What is a list?**  
  A: A collection that stores multiple items in one variable.
- **Q: Why do we use functions?**  
  A: To reuse a block of code and keep programs organised.

### 2. Breadth-First Search and Depth-First Search
- **Q: What is BFS?**  
  A: Breadth-First Search visits nodes level by level.
- **Q: Which data structure does BFS use?**  
  A: A queue.
- **Q: Which data structure can DFS use?**  
  A: A stack or recursion.

### 3. A* Search Algorithm
- **Q: What does A* do?**  
  A: It searches for a low-cost path from a start node to a goal.
- **Q: What is g(n)?**  
  A: The cost from the start to the current node.
- **Q: What is h(n)?**  
  A: An estimate of the remaining cost to the goal.

### 4. Tic-Tac-Toe using Minimax
- **Q: What is Minimax?**  
  A: A search method for choosing moves in two-player games.
- **Q: What does the maximising player do?**  
  A: Chooses the move with the highest score.
- **Q: Why is the board restored after testing a move?**  
  A: So each possible move is evaluated from the same original position.

### 5. Knowledge Representation using Facts and Rules
- **Q: What is knowledge representation?**  
  A: A way of storing facts and relationships so a computer can use them.
- **Q: What is a rule?**  
  A: A condition that lets a system draw a conclusion.
- **Q: Is this example a complete real-world bird model?**  
  A: No. It is a small demonstration of facts and rules.

### 6. Bayes' Theorem / Simple Naive Bayes
- **Q: What is Bayes' theorem used for?**  
  A: To update a probability using new evidence.
- **Q: What does P(A|B) mean?**  
  A: The probability of A given that B has happened.
- **Q: What is Naive Bayes?**  
  A: A probabilistic classifier that assumes features are conditionally independent given the class.

### 7. Linear Regression and Decision Tree
- **Q: What is regression?**  
  A: Predicting a continuous numeric value.
- **Q: What is classification?**  
  A: Predicting a category or class label.
- **Q: How does a decision tree work?**  
  A: It splits data using feature-based questions or conditions.

### 8. K-Means Clustering
- **Q: What is clustering?**  
  A: Grouping similar data points together.
- **Q: Is K-Means supervised or unsupervised?**  
  A: Unsupervised.
- **Q: What does K represent?**  
  A: The number of clusters to create.

### 9. Basic Natural Language Processing
- **Q: What is NLP?**  
  A: A field of AI that enables computers to work with human language.
- **Q: What is tokenisation?**  
  A: Splitting text into smaller units such as words.
- **Q: Why convert text to lowercase?**  
  A: To treat words like 'AI' and 'ai' as the same token.

### 10. Mini AI Project: Student Result Predictor
- **Q: What is the input in this project?**  
  A: Study hours and attendance percentage.
- **Q: What is the output?**  
  A: The predicted class: Pass or Fail.
- **Q: Why is the dataset only for demonstration?**  
  A: It is very small and does not represent all real student situations.

## Last-minute routine
1. Say the aim of the practical in one sentence.
2. Identify the input, main algorithm/function, and output.
3. Type the code yourself without looking, then compare.
4. Explain each import and each function in simple words.
5. Remember that output may vary slightly for clustering because cluster labels can be swapped.