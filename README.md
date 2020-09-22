# CSCE-315-The-Butterfly-Effect

Developed Donald Hacker, Nick Cashiola, and Ryan Clark


## Project Overview


The Butterfly Effect is a web-based application that intends to aggregate all useful information on a given topic into a single destination. Currently, users of social media have to travel to different sites in order to obtain specific information on trending topics. The Butterfly Effect changes this by displaying trending topics, corresponding descriptions, and financial data all on one page. With the click of a button, users of the Butterfly Effect are able to view all relevant information on a given topic. 
    
 The final design of the Butterfly Effect uses React to interface with the front-end user experience and NodeJS to obtain data on the back-end of our application. The React component of the application allowed for rendering discrete objects in HTML. This was utilized in the rendering of the data obtained from the APIs used. The NodeJS back-end of the application uses APIs from Wikipedia, Twitter, and Alpha Vantage. The information obtained from these APIs is then passed to React in order to be rendered. Additionally, sentiment analysis is conducted with an NPM module on the back-end. The sentiment score is then passed to the front-end for rendering. Along with the sentiment score, financial information, general information, and popular tweets are rendered on the webpage. A more detailed description of the rendered elements can be found in the User Manual Section below.
    
 The Butterfly Effect, as it currently stands, is an easy-to-use information aggregator. Users can see financial data, a general description, a sentiment score, and popular tweets about any topic that is searched. The general description of any topic is obtained using the Wikipedia API and displays on the trending page. Financial information for specific companies is displayed when the user searches a listed company ticker; otherwise, the data concerning the Dow Jones Industrial Average is displayed. A sentiment score (color coded for negative, neutral, and good scores) is displayed when the user searches for any topic. Finally, five popular tweets (written in English) display for every search the user makes. 
    
This project utilized an agile method of development. Using agile methodology for development requires proactive planning and documentation as well as frequent team meetings. Our team quickly adjusted to the frequent meeting schedule and created the necessary documentation for the project before the first sprint began. The documentation was not updated optimally during the sprints, but overall progress was tracked well in the product backlog and the product burn down chart. Overall, the team quickly adapted to the agile framework and worked well together to complete the project.
