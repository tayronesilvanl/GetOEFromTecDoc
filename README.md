# TecDoc Web Scraper

This is a JavaScript script that allows you to collect automotive parts information from TecDoc and export it to a CSV file. The script navigates through web pages, extracts part number and OE code information, and then generates a CSV file with the collected data.

## Requirements

- A web browser with JavaScript support (we recommend Google Chrome).
- Node.js installed to run the script in the Node.js environment.

## How to Use

1. Clone this repository to your computer.

2. Open the terminal and navigate to the project folder.

3. Install Node.js dependencies by running the following command:

   ```bash
   npm install
Edit the scraper.js file to configure collection options, such as the desired number of Part Numbers and wait times.

Execute the script with the following command:

node scraper.js
The script will start collecting information about automotive parts from TecDoc.

The script will print the progress of the collection on the screen, including the Part Number and OE codes for each part.

Upon completion of the collection, a CSV file named part_numbers.csv will be generated in the project folder with the collected data.

Configuration
In the scraper.js file, you can adjust the following options:

desiredPartNumbers: Change it to the desired number of Part Numbers to collect or set it to -1 to check all.

maxPartNumbersBeforeWait: Change it to the number of Part Numbers before adding extra wait.

extraWaitTime: The extra wait time in milliseconds (7 seconds) when the extra wait is triggered.

Please note that collecting a large number of parts may take some time. Make sure to adjust the settings according to your needs.

Contribution
Feel free to contribute to this open-source project. If you encounter issues or have improvements to suggest, open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.


Certify to replace "your-username" e "your-repository" .
