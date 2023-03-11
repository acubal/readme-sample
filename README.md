# {Project Name} Repository Guide

This is a guide on how to clone a repository using GIT GUI of Github or Sourcetree, or Git command line, include the latest .env file and install dependencies using Composer.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Clone using Github](#clone-using-github)
- [Clone using Sourcetree](#clone-using-sourcetree)
- [Clone using Git command line](#clone-using-git-command-line)
- [Get the latest env file](#get-the-latest-env-file)
- [Install dependencies using Composer](#install-dependencies-using-composer)
- [Conclusion](#conclusion)

## Prerequisites

Before cloning a repository, including the latest .env file and installing dependencies using Composer, you will need to have the following:

- A Github account
- A computer with Git and Composer installed
- List of PHP Extensions:
  - curl
  - exif
  - fileinfo
  - gd
  - intl
  - mbstring
  - mysqli
  - openssl
  - pdo_mysql
  - xsl

## Clone using Github

1. Open the Github website and navigate to the repository you want to clone.
2. Click on the "Code" button and select "HTTPS".
3. Copy the HTTPS URL provided.
4. Open the Git GUI of Github on your computer.
5. Click on "Clone a repository".
6. Paste the HTTPS URL in the "URL" field and choose the destination folder for the repository.
7. Click on "Clone" to start the cloning process.

## Clone using Sourcetree

1. Open Sourcetree on your computer.
2. Click on "Clone" in the toolbar.
3. Paste the HTTPS URL of the repository you want to clone in the "Source Path / URL" field.
4. Choose the destination folder for the repository.
5. Click on "Clone" to start the cloning process.

## Clone using Git command line

1. Open your terminal or command prompt.
2. Navigate to the folder where you want to clone the repository.
3. Use the following command to clone the repository:

        git clone https://github.com/{username}/{repository}.git

    Replace "username" with the actual Github username and "repository" with the name of the repository you want to clone.
4. Press Enter to execute the command and start the cloning process.

## Get the latest env file

1. Open the repository folder using VSCode or any text editor of your choice.
2. Navigate to the root of the project and look for the `.env.example` file.
3. Make a copy of the `.env.example` file and rename it to `.env`.
4. Contact the repository owner for the correct values to put in the `.env` file, or refer to the documentation if available.
5. Store the `.env` file in the root of your project folder on your computer.

## Install dependencies using Composer

1. Open your terminal or command prompt.
2. Navigate to the folder where you cloned the repository.
3. Use the following command to install dependencies using Composer:

        composer install

4. Press Enter to execute the command and start the installation process.

## Conclusion

You have now learned how to clone a repository using Git GUI of Github, Sourcetree, or Git command line, include the latest .env file and install dependencies using Composer. Happy coding!
