# fCC Forum Leaderboard

This project is a dynamic leaderboard that displays the latest topics from the freeCodeCamp forum. It retrieves data from the freeCodeCamp forum API and displays it in a tabular format, including topic titles, avatars of posters, replies, views, and the time of the last activity.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Code Overview](#code-overview)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)


## Features

- Displays the latest topics from the freeCodeCamp forum.
- Shows topic titles, avatars of users, the number of replies, views, and time since the last activity.
- Links to individual topics and categories within the freeCodeCamp forum.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Fetch API**

## Code Overview

### HTML

The HTML structure consists of a header with a navigation logo and a main section that contains a table. The table is dynamically populated with data retrieved from the freeCodeCamp forum API.

### CSS

The styling is managed via an external stylesheet, `styles.css`, which provides a clean and responsive layout for the leaderboard table.

### JavaScript

- **Fetch API**: Used to fetch the latest topics from the freeCodeCamp forum API.
- **Dynamic Content**: JavaScript is used to dynamically create and insert table rows based on the fetched data.
- **Utility Functions**: Includes helper functions for formatting view counts, calculating time ago, and generating avatars.

## Future Enhancements

- Add pagination to navigate through more topics.
- Implement filtering and sorting options for the topics.
- Add a search bar to quickly find specific topics.
- Feel free to add contributions!

## Contributing

If you would like to contribute, please feel free to submit a pull request or open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

