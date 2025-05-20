# Country Info Lookup Chatbot (via Console)

This project is a console-based chatbot built using n8n that allows users to input a country name and retrieve detailed information about that country, including its capital, region, population, currency, and national flag.

Features

- Lookup information for any country by name
- Uses the REST Countries API for accurate and up-to-date data
- Displays:
  - Country Name
  - Capital
  - Region
  - Population
  - Currency
  - Flag URL
- Runs entirely in the console
- Beginner-friendly automation with real-world API integration

Workflow Overview

Step | Node | Description
-----|------|------------
1 | Execute Command | Accepts input of the country name (e.g., India)
2 | Function Node | Formats the input string for API compatibility
3 | HTTP Request | Sends a request to the REST Countries API
4 | Function Node | Extracts relevant fields from the response
5 | Execute Command | Outputs the data back to the console

How to Use

1. Open your n8n editor (local or hosted).
2. Create a new workflow.
3. Add the listed nodes in the specified order.
4. In the first node (Execute Command), input a sample country (e.g., "India").
5. Run the workflow to see the output in your console or logs.

Sample Output

Country: India  
Capital: New Delhi  
Region: Asia  
Population: 1380004385  
Currency: Indian rupee  
Flag: https://flagcdn.com/w320/in.png

Author

LinkedIn: [ashleymathia10](https://www.linkedin.com/in/ashleymathia10)  
GitHub: [AshleyMathias](https://github.com/AshleyMathias)

License

This project is released under the MIT License.
