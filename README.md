# 🛠️ Zulu N Stitch

Zulu N stitch is a premium African cloth line store, fabric from the land and skill of the hand, touched by artists.

---

## 🚀 Clone the Project

First things first — open your terminal and run:

```bash
git clone https://github.com/mithibe/Zulu-n-Stitch.git
cd Zulu-n-Stitch
````
---

## 💎 Install Ruby Gems (Dependencies)

Make sure you have Ruby and Bundler installed on your system. Then install all the Ruby gems the project needs by running:

```bash
bundle install
```

This will read the `Gemfile` and install all the required libraries.

---

## 🗃️ Set Up the Database

Now let’s set up the database.

First, make sure your database (e.g. PostgreSQL or SQLite) is installed and running. Then run the following:

```bash
rails db:create
rails db:migrate
rails db:seed # (optional – only if you have seed data)
```

These commands will create your database, apply any database schema (migrations), and optionally fill it with demo data.

> 💡 If you run into errors, double-check your `config/database.yml` file for correct database settings.

---

## 🌐 Start the Server

Now, you’re ready to run the app!

Start the Rails server with:

```bash
rails server
```

Then, open your browser and go to:

```
http://localhost:3000
```

If everything worked, your Rails app should be up and running locally 🎉.

---

## 🧪 Run the Tests (Optional)

If this project includes tests (like RSpec or Minitest), you can run them with:

```bash
# RSpec
bundle exec rspec

# OR Minitest
rails test
```

---

## 🧰 Common Errors & Fixes

**⚠️ `rails db:create` failed?**
Make sure your database service is installed and running (e.g. `postgresql`).

**⚠️ Port 3000 is already in use?**
Start the server on a different port with `rails s -p 3001`.

---

## 📎 Useful Links

* [Ruby on Rails Guides](https://guides.rubyonrails.org/)
* [Ruby Documentation](https://www.ruby-lang.org/en/documentation/)
* [PostgreSQL Setup Guide](https://www.postgresql.org/docs/)

---

## 🤝 Contributing

If you want to contribute:

1. Fork this repository
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes
4. Push to your fork (`git push origin feature-name`)
5. Open a pull request

Let’s build something great together!

---

## ✨ License

None at the moment.

---

> Made with ❤️ and `rails new` by [@mithibe](https://github.com/mithibe)
