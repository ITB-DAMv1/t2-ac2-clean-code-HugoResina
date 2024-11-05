# Clean Code
## A Handbook of Agile Software Craftsmanship
* ### Chapter 1
    - This first chapter focuses on the idea of “clean code” and why it is important for aspiring programmers. A clean code, doesn’t have to be only functional but also readable, sustainable and somewhat elegant. That implies following some rules, like the “boy scout” rule, that encourages us to leave our code better than how we found it, just to name an example. It is also remarked the importance of having a proactive attitude towards writing clear code so that it is easily understood.
* ### Chapter 2
    - The second character is pretty self-explanatory, as its title suggests, using descriptive names that reflect function or purpose makes the code more readable. It is recommended to avoid abbreviations or names with confusing meanings and to try and sustain a global coherence to facilitate the code comprehension, therefore contributing to a clearer and less ambiguous code and helping its collaboration and long-term handling


* ### Chapter 3
    - In order for a code to be considered clean, one of its requirements is for its functions to be as small as possible and to try to follow the “do one thing” rule, where any function develops a single task. It is also advised to follow the Stepdown rule, where the code is structured from top to bottom, improving its readability
* ### Chapter 4
    - Comments should be kept to a minimum and only used where necessary to make complex things clearer. The main purpose is to avoid useless or redundant comments that may induce errors, though it is preferable for code to be self explanatory rather than depending on comments. Therefore, comments should be reserved to cases where code cannot be clarified further

* ### Chapter 5
    -    Formatting refers to how the lines of code themselves are structured, like leaving blank spaces between ideas. To help identify different sections of the code, it is preferable to opt for files of reasonable size, and that are easy to understand and maintain following the diary metaphor, where the most important sections appear at the beginning and details further ahead


* ### Chapter 7
    - To handle errors, it is best to use exceptions rather than return codes, because they provide more contextual information. It is recommended to avoid returning null values and to establish the error flux at the beginning of the code with try-catch blocks, this helps to maintain a cleaner code and a clear flux that minimizes the complexity of handling errors

