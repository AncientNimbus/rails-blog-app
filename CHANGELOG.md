## [unreleased]

### 🚀 Features

- Add article and db schema
- Display all articles on root page
- Add the ability to read articles
- Add the ability to create articles
- Add the ability to delete an article
- Add comment model
- Add the ability to comment on an article
- Add status field to the db
- Add the ability to delete comments

### 🐛 Bug Fixes

- Address Rubocop offense
- Add missing db env variable
- Attempt to skip solid manually
- Modify cable.yml
- Remove solid cache
- Modify docker entrypoint to use db migrate
- Modify the script to only migrate db

### 🚜 Refactor

- Replace get with resource
- Create partials views for comments

### ⚙️ Miscellaneous Tasks

- Add solargraph to Gemfile
- Add ERBLint to Gemfile
- Add rubocop-erb to Gemfile
- Bump actions/checkout from 4 to 5 (#1)
- Add BSD 3-Clause License
- Generate rbs_collection
- Bump solargraph-rails from 1.1.0 to 1.2.2 (#2)
- Update dockerfile and env config for hosting
- Update DB to use PostgreSQL
- Update workflows file to support pg test
- Test custom domain setup
