# React E-commerce Application

This is a simple React-based e-commerce application that allows users to browse and purchase products. The application provides various features such as product filtering, category selection, and cart functionality.

## Features

- Browse products: Users can view a list of available products with their names, prices, and descriptions.
- Filter products: Users can filter products based on categories and price ranges.
- Category selection: Users can choose specific categories to narrow down their product search.
- Cart functionality: Users can add products to their cart and proceed to checkout.
- Load more: Products are loaded dynamically as the user scrolls down the page.
- Responsive design: The application is designed to work well on different screen sizes.

## Technologies Used

- React: JavaScript library for building user interfaces.
- React Router: Library for routing in a React application.
- Ant Design: UI component library for React.
- Axios: Promise-based HTTP client for making API requests.
- react-hot-toast: Library for displaying toast notifications.
- HTML/CSS: Markup and styling for the application.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install dependencies:

   ```bash
   cd your-repository
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open your browser and visit `http://localhost:3000` to see the application.

## Configuration

- API Endpoint: The application expects the API to be available at `/api/v1` on the same domain. Make sure to configure the API endpoint accordingly.

## Folder Structure

- `src/components`: Contains reusable components used throughout the application.
- `src/context`: Contains the cart context used for managing the cart state.
- `src/styles`: Contains CSS stylesheets for the application.
- `src/pages/HomePage.js`: The main page component that displays the list of products and provides filtering options.
- `src/App.js`: The root component that sets up the application routes.
- `src/index.js`: The entry point of the application.

## Contributing

Contributions to the project are always welcome. Here are a few ways you can contribute:

- Report issues or bugs
- Suggest new features or improvements
- Submit pull requests

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your needs.