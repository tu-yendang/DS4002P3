# DS4002P3
## Software and Platform
* The primary software used for this project was Python, specifically using Interactive Python Notebook files (ipynb). These files were created and used with Google Colab and Rivanna. Data was gathered on Google Colab by using webscraping.
* The following packages were used to gather data:
    * BeautifulSoup - parses HTML content to allow easy access to web page elements
    * display - render HTML or other outputs
    * HTML - allows for embedding HTML content directly
* 
* Three laptops were used, where two devices used Mac, while one was conducted on Windows.
## Documentation Map
The following is a map of our project's repository.
* DS4002P3 (main directory)
 * DATA - folder
   * book_covers_images.csv
   * test_book_covers.csv
   * train_book_covers.csv
 * OUTPUT - folder [TBD]
 * SCRIPTS - folder
   * model_analysis.ipynb
   * preprocessing.ipynb
 * LICENSE.md
 * README.md
## Reproducing Results Instructions
In this section, you should give explicit step-by-step instructions to reproduce the Results of your study. These instructions should be written in straightforward plain English, but they must be concise, but detailed and precise enough, to make it possible for an interested user to reproduce your results without much difficulty. N.B. This section will be crucial for the CS1 assignment, where you'll be required to reproduce the results of other groups. Therefore, make sure to explain this section thoroughly.

In order to complete this study, users should:
1. Collecting Data: Find and collect data from GoodReads Readers' Favorite Books site from 2019-2024 [2] separated into 13 genres. This is already set up in the preprocessing file of the code with the following genres: Fantasy, Fiction, Historical Fiction, Mystery & Thriller, Romance, Science Fiction, Horror, Young Adult Fantasy, Young Adult Fiction, Humor, History & Biography, Memoir and Autobiography, and Nonfiction.
2. Preprocessing/Splitting Data: While running the preprocessing file, the image URL of the book covers will be gathered, along with their respective genres. It will also combine all the collected data for each genre into 2 CSV files: training and testing (train_book_covers.csv and test_book_covers.csv). Training data will be around 83% of the total data, while testing will account for the rest.

3. Model analysis: Now that the data is properly formatted and split, the data can be used for analysis. In this analysis, we will use the model_analysis python notebook and run it on Rivanna on the files. Google Colab can also be used, however Rivanna is significantly faster to run. For a program this computationally high/complex, Rivanna is recommended. This may take a while, but the code will do the following:
    * 