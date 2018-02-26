# comp130-software-engineering
There a multiple ways to check for collisions from different objects, but which one provides the best performance when checking for multiple collisions at once, continuously while a game is running? This problem stems from it not being immediately obvious how having objects checked uses resources.

To address this question I will very quickly introduce the idea to the reader and then start to take a look at some different possible ways of checking for collisions in video games. Then go on to look at the time and memory allocations required for these to be completed. I will also look at how scalable they are by increasing the size of the tests to check for tipping points where one may become more useful than the previous one was.

I will extensively use papers previously published for ideas on good collision detection systems and use the information given to form a basis of my paper. I may look into testing the algorithms myself to get some clear comparisons if the data I find in the research papers isn’t enough for me to use.

The comparisons will be clear and concise, taking advantage of graphs to easily show the resource usage of the different algorithms. The algorithms themselves will be shown in pseudo code allowing for application across the board and ease of understanding incase a reader is not familiar with a specific language.

I will do some referencing of my current experiences using collision detection in a game where there are multiple collisions possible, how we have chosen to handle it and how this has been going for us. 

It’s possible that there may not be much difference in the performance given from using different algorithms. However I feel like that would still be a good outcome for the paper as it allows the reader to sit comfortably choosing the one they prefer.

The conclusion of my paper will leave the reader with a set choice of algorithm types to be used for collision detection depending on the amount of checks being done and the frequency of the checks.
