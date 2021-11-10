# hello-rails-back-end

## Table of Contents

- [About the Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Contributing](#contributing)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

## About Project

This is practice project on working with Ruby on Rails and React together. In this project I have implemented the backend with Ruby on rails. This backend is API only.

[Link to the FRONTEND part of this project.](https://github.com/Lameck1/hello-react-front-end)

## Built With

- Ruby v3.0.2
- Rails 6.1.2
- Postgresql

## Getting Started

- Clone this repo https://github.com/Lameck1/hello-rails-back-end

  ```bash
  git clone https://github.com/Lameck1/hello-rails-back-end.git
  ```

- Navigate to hello-rails-back-end folder/directory

  ```bash
  cd hello-rails-back-end
  ```

- On the terminal, while in the 'hello-rails-back-end' directory, run the following to install dependencies:

  ```bash
  bundle install
  ```

- At this point, you still don't have the PostgreSQL database. Run the following to get setup:

  - Ensure that postgresql service is up and runnning

    ```bash
    sudo service postgresql start
    ```

  - Create the database

    ```bash
    rails db:create
    ```

  - Migrate the database

    ```
    rails db:migrate
    ```

  - Run `rails db:seed` to quickly get setup with sample data for testing the app.

- To interact with the project's API, run:

  ```
  rails server
  ```

  OR

  ```
  rails s
  ```

- Run the frontend part of the project.

### Prerequisites

- Ensure you have these installed:

  - Git
  - Ruby 3.0.2
  - Ruby on rails `gem install rails`

- You also need to ensure your yarn is upto date
  ```
  yarn install --check-files
  ```

## Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Lameck1/hello-rails-back-end/issues).

## Author

👤 **Lameck Otieno**

- GitHub: [@githubhandle](https://github.com/Lameck1)
- Twitter: [@twitterhandle](https://twitter.com/lameck721)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/lameck-odhiambo-642b7077/)

## Acknowledgements

Credits go to the following for providing guides on Ruby on Rails

- [**Rails Guides**](https://guides.rubyonrails.org)

## Show your support

Give a ⭐️ if you like this project!
