# The Blog app

Blog website that shows a list of posts and empower readers to interact with them by adding comments and liking posts.

## Built With

- Ruby on Rails
- PostgreSQL

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/)
- [Rails](https://gorails.com/)

### Setup

- Make sure you have Ruby on Rails set up properly on your computer
- Clone or download this repo on your machine
- Enter project directory

### Development Database

```sh
# Create user
sudo -u postgres createuser blog -s

# Create the database
rake db:create
```

### Install

```sh
bundle install
```

### Run

```sh
rails s
```

### Test
to run tests use bundle exec before like;
```bundle exec rspec spec
```

## Authors

👤 **Isaka Lumato**

- GitHub: [@isaacLumato](https://github.com/isaka-lumato)
- Twitter: [@isaacLumato](https://twitter.com/@lumatoisaac)
- LinkedIn: [isaacLumato](https://www.linkedin.com/in/isaac-lumato/)

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse

## License

[MIT](./LICENSE)
