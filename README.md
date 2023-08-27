# Portfolio Visualizer

This repository contains a React application that allows you to visualize the historical value of tokens on the Avalanche C-Chain in a given wallet address using Covalent API data and Recharts library.


## Introduction

Portfolio Visualizer is a React application that fetches token portfolio data from the Covalent API based on a provided wallet address. It then uses the Recharts library to display the historical value of each token in the portfolio over time in the form of a line chart.

## Setup

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Obtain a Covalent API key:
   
   You'll need to sign up for a Covalent API key to fetch the necessary data. Once you have your API key, create a `.env` file in the root directory of the project and add your key:

   ```
   REACT_APP_COVALENT_API_KEY=your-api-key
   ```

4. Run the application:

   ```bash
   npm start
   ```

5. Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to see the Portfolio Visualizer in action.

## Usage

1. On the Portfolio Visualizer webpage, you'll see an input box labeled "Enter wallet address." 

2. Input the wallet address for which you want to visualize the portfolio data.

3. Click the "Submit" button.

4. The application will fetch the portfolio data using the Covalent API and generate a line chart using the Recharts library to display the historical value of each token in the portfolio over time.

5. Each token is represented by a different color on the line chart.

