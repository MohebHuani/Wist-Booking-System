# Wist Academy Hotel System For Eng Moheb Huani

[//]: # (A REST API program for hotel reservation, powered by Laravel. This project is designed to work similarly to the hotel reservation section on www.alibaba.ir)

## Features

    Database design based on host and hotel management
    Management of the application using laravel-admin
    Authentication using Sanctum
    Storage of files in cloud storage

## Packages Used

### This project uses the following packages:

    horizon
    telescope
    flysystem-aws
    phpspreadsheet
    spatie-medialibrary
    scrib
    laravel/sanctum
    laravel/scout
    meilisearch-php
    predis

### Installation

    Clone the repository:
    git clone https://github.com/MohebHuani/Wist-Hotel-System-For-Eng-Moheb-Huani.git

    Navigate to the project directory:
    cd Wist-Hotel-System-For-Eng-Moheb-Huani

    before install composer Please turn on VPN

    Install dependencies:
    composer install

    Set up environment variables:
    cp .env.example .env and configure your environment variables in the .env file
    
    Generate a key:
    php artisan key:generate 

    Run the migrations and seed:
    php artisan migrate --seed

    Start the development server: 
    php artisan serve


