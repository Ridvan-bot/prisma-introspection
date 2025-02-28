# prisma-introspection

![Build Status](https://github.com/Ridvan-bot/prisma-introspection/actions/workflows/deploy.yml/badge.svg)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/Ridvan-bot/prisma-introspection?label=version&sort=semver)
![Last Commit](https://img.shields.io/github/last-commit/Ridvan-bot/prisma-introspection)
![GitHub issues](https://img.shields.io/github/issues/Ridvan-bot/prisma-introspection)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Ridvan-bot/prisma-introspection)

## Overview

Use this tool to create a Prisma schema from an existing database.

## Setup

1. Create a `.env` file containing your database connection string. If your database name contains special characters like "ö", make sure to URL-encode them. For example, "ö" becomes "%C3%B6".

2. Install the necessary dependencies:
    ```sh
    npm install
    ```

3. If you don't use Microsoft SQL, change the DB provider in `schema.prisma`.

## Usage

1. Pull the database schema:
    ```sh
    npx prisma db pull
    ```

2. Generate the Prisma client:
    ```sh
    npx prisma generate
    ```

## Contributing

Feel free to open issues or submit pull requests if you have any improvements or bug fixes.

## License

This project is licensed under the MIT License.

<p align="center">
  Crafted with care by <strong>Robin Pohlman</strong> at <strong>Pohlman Protean AB</strong>.
</p>