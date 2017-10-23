# 5216assignment
USYD-2017S2-mobile-computing-assignment-swift-Quz Game App
SudentID: 460094203(zwan4387)
Full name: zhiliang wang
## Instructions of how to understand source code
- The source code is divided into three parts which are **'Controller','Custom'and 'Questions'**;
    - In the 'Controller' group, 'MenuViewController','MultipleChoiceViewController','ImageQuizViewController','RightOrWrongViewController' and 'GenericQuizViewController' were used in the project.
        - 'MenuViewController' is responsible for building basic layout, creating buttons, labels, constraints, inserting backgound music and preserve marks and so on .
        - 'MultipleChoiceViewController' is reponsible for building multiple choices layout, creating buttons, labels, constraints in this section, making a timer for ansering each question and so on.
        - 'ImageQuizViewController' is reponsible for building image quiz layout, creating buttons, labels, constraints in this section, making a timer for ansering each question, use random function to split each image into 9 small parts and so on.
        - 'RightOrWrongViewController' is reponsible for building ROW quiz layout, creating buttons, labels, constraints in this section, making a timer for ansering each question and so on.
        - 'GenericQuizViewController' is the general templates for other view controllers.
    - In the 'Custom' group, 'RoundedButton','RoundedLabel','Constants+Extensions','QuizLoader','QuizAlertView' were used.
        - 'RoundedButton' and 'RoundedLabel' identified the basic shape used in the layout.
        - 'QuizLoader' is the bridge of plist file and quizs.
        - 'QuizAlertView' is the reminder of alertion for wrong answers in the process of quiz.
    - In the 'Questions' group, it shows three different types of quizs.
    - Multiple choice quiz:
        - [Questions] is an Array, includes many [items] which is a Dictionary type;
        - Each [item] has [[String]Answers,[String]correctAnswer,[String]Question];
        - Each [Answer] Array includes four [String] items which means four options in each [String] Question.
    - Image quiz:
        - [Questions] is an Array, includes many [items] which is a Dictionary type;
        - Each [item] has [[String]Answers,[String]correctAnswer,[String]Question];
        - Each [Answer] Array includes four [String] items which means four options in each [String] Question.
        - [String]Question should import images from 'Resources';
    - ROW quiz:
        - [Questions] is an Array, includes many [items] which is a Dictionary type;
        - Each [item] has [[String]correctAnswer,[String]Question];
   
    


