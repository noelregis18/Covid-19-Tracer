# COVID-19 Tracker

A React application to track COVID-19 cases globally and by country, providing real-time statistics and visualizations.

![COVID-19 Tracker](./src/images/image.png)

## Features

- **Global Statistics**: View worldwide COVID-19 data including confirmed cases, recoveries, and deaths
- **Country-Specific Data**: Filter statistics by selecting specific countries
- **Interactive Charts**: Visualize data through line charts (global trends) and bar charts (country-specific)
- **Responsive Design**: Fully responsive UI that works on desktop and mobile devices
- **Real-time Data**: Fetches the latest COVID-19 data from a reliable API

## Technologies Used

- **React**: Frontend library for building the user interface
- **Material-UI**: React components for faster and easier web development
- **Chart.js**: JavaScript charting library for data visualization
- **Axios**: Promise-based HTTP client for API requests
- **React CountUp**: React component wrapper around CountUp.js to animate numbers
- **Express**: Server-side framework for SSR (Server-Side Rendering) support

## API

This application uses the [COVID-19 API](https://covid19.mathdro.id/api) by Mathdro to fetch real-time COVID-19 data.

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/covid19_tracer.git
   cd covid19_tracer
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm start
   # or
   yarn start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `yarn build`

Builds the app for production to the `build` folder.

### `yarn deploy`

Deploys the app to GitHub Pages.

### `yarn ssr`

Runs the app with server-side rendering using Express.

## Deployment

This app is configured for deployment to GitHub Pages. Run the following command to deploy:

```bash
yarn deploy
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- [Mathdro](https://github.com/mathdroid/covid-19-api) for the COVID-19 API
- [Material-UI](https://material-ui.com/) for the UI components
- [Chart.js](https://www.chartjs.org/) for the data visualization
