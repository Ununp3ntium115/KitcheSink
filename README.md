# KitcheSink
Web Scrapper that allows for processing of search terms in a loop while collecting data and storing it in a DB that can be processed by a LLM
Here is a high-level overview of the core classes, functions, and methods that will be necessary:

1. `WebScraper`: This class will handle the web scraping part. It will have methods to navigate to a URL, follow links, and extract images.

2. `ImageProcessor`: This class will handle the image processing part. It will have methods to break an image into chunks.

3. `DatabaseManager`: This class will handle the database management part. It will have methods to store and retrieve image chunks.

4. `RandomTermGenerator`: This class will handle the random term generation part. It will have methods to generate a random term from a dictionary or based on trending topics.

5. `main`: This function will be the entry point of the application. It will create instances of the above classes and coordinate their actions to achieve the desired functionality.
