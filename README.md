# Avalanche Token Portfolio Visualizer

## Introduction

The Avalanche Token Portfolio Visualizer is a dynamic and versatile React application, tailored to cater to the diverse needs of users within the Avalanche ecosystem. With a robust integration of React's capabilities, Covalent APIs, and added enhancements, this project now empowers users to delve even deeper into the historical value of tokens not only on the Avalanche C-Chain but across various Avalanche subnets. The seamless collaboration of technology and innovation opens doors to enhanced insights and informed decisions for token holders.

## Key Features

- **Enhanced Chain Selection**:  users can now select not just the Avalanche C-Chain, but also explore token values on various Avalanche subnets, thanks to the expanded list of available chains.

- **Seamless Interface Experience**: Powered by React, the application boasts an intuitive and responsive interface, ensuring users enjoy a seamless experience while navigating through various features.

- **Covalent APIs for Comprehensive Data**: The integration with Covalent APIs remains pivotal, allowing the application to provide users with comprehensive and accurate historical token pricing data across the Avalanche ecosystem.

- **Extended Input Field**: The "Enter wallet address" input field has been extended and refined to offer more space, ensuring user convenience during input.

## How It Works

1. **Chain Selection**: Users can choose the specific Avalanche chain or subnet they wish to explore. The extended list of available chains includes various subnets alongside the Avalanche C-Chain.

2. **User Interaction**: Similar to the earlier version, users input a wallet address within the chosen chain or subnet, initiating the data retrieval process.

3. **Covalent API Integration**: The application communicates with the chosen Covalent API to retrieve historical token pricing data for the provided wallet address.

4. **Data Transformation**: The fetched data undergoes transformation to facilitate clear and effective visualization, enabling users to discern patterns and trends in token value evolution.

5. **Visualization with React and Recharts**: React, in conjunction with the Recharts library, crafts interactive line charts that vividly depict the historical trajectory of each token's value. The Y-axis is now labeled as "Value in USD" for user clarity.

## Get Started

To embark on this enhanced visualization journey:

1. Clone the repository and navigate to the project directory.
2. Install dependencies using `npm install`.
3. Acquire a Covalent API key and add it to your `.env` file.
4. Launch the application using `npm start`.
5. Access the application via [http://localhost:3000](http://localhost:3000), select the desired chain or subnet, input your wallet address, and uncover insightful visualizations.

