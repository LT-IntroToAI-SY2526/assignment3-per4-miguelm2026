# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?

Through this assignment, I gained a deeper understanding of how to effectively use functions, I learned more how functions can be structured and used to handle specific tasks within a program. Compared to my first assignment, I now feel more confident in defining and using functions to organize code logically and make it useale again.

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.

The movie chatbot relies on a set of projection functions designed to extract specific pieces of information from the user’s input, such as the movie title, director, year, or actors. When a user types a query, the system uses pattern matching techniques to check if the input fits certain templates. If the query is incomplete or missing some details, the chatbot prompts the user to provide that missing information. Once it has all the necessary data, it searches the movie database to find matching entries and returns the relevant answer.

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

This kind of chatbot could be really helpful when someone only knows part of the info and needs help finding the rest, like in customer support or answering common questions. To make it better, I’d connect it to an API so it can get movie info automatically instead of having to add everything by hand. That way, it’d be easier to keep updated and have more movies.