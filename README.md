# FitFinder
Create a streamlined console application that seamlessly retrieves the latest deals from prominent gym chains in Canada, while also offering a user-friendly general search functionality. 

<!-- FitFinder Console Application -->

<h1>Description</h1>

<p>FitFinder is a Java console application designed to provide users with two powerful features related to gym memberships. It utilizes web scraping and crawling techniques to offer the following functionalities:</p>

<!-- 1. Gym Membership Deals -->

<h2>Gym Membership Deals</h2>

<p>FitFinder fetches the best deals for a gym membership from three popular gym websites: GoodLife Fitness, Planet Fitness, and Fitness World. Users can input the city name, either by adding it manually or selecting from the history. The program supports users by providing word completion and spellchecking during city name input, and consulting a local dictionary for assistance.</p>

<!-- Feature Highlights -->

<h4>Feature Highlights:</h4>

<ul>
  <li>Web Scraping: Utilizes Selenium to scrape data from GoodLife Fitness, Planet Fitness, and Fitness World.</li>
  <li>Console Display: Presents the best deals on the console.</li>
  <li>CSV Data Export: Saves the scraped data in CSV files for future reference.</li>
  <li>User-Friendly Input: Supports manual city input, lookup from history, word completion, and spell checking.</li>
</ul>

<!-- 2. Gym-Related Query Search -->

<h2>Gym-Related Query Search</h2>

<p>FitFinder allows users to search for gym-related queries on the console and provides the best URLs with the highest frequency of the searched keyword. The program crawls a gym blog website up to 2 levels and creates a database of URLs to search from. The feature consults this database to provide the best websites in descending order based on the highest occurrence of keywords, along with a count of keyword occurrences.</p>

<!-- Feature Highlights -->

<h4>Feature Highlights:</h4>

<ul>
  <li>Web Crawling: Crawls a gym blog website up to 2 levels to create a database of URLs.</li>
  <li>Keyword Search: Consults the database to provide URLs based on keyword occurrences.</li>
  <li>Results Display: Presents URLs in descending order of keyword occurrences with assurance counts.</li>
</ul>

<h2>Dependencies</h2>

<p>To run FitFinder, ensure you have Java installed on your system. Additionally, this program uses Microsoft Edge to scrap websites to get appropriate web drivers from this <a href="https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/#downloads">link</a>. </p>

<!-- Contact -->

<h2>Contact</h2>

<p>For any inquiries or feedback, please contact Bhautik Savaliya at bhautiksavaliya2000@gmail.com</p>
