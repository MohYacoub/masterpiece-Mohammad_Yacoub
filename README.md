# masterpiece-Mohammad_Yacoub

## Project Description

INTRODUCTION TO THE
JOHUD SYSTEM
This system aims to provide and facilitate the processes of
establishing the activities of the Jordanian Hashemite Fund for
Human Development (JOHUD), which enables the user to display
the data And the information he needs easily without referring to
tired records and paper references and contributes to showing the
necessary reports .

##login(Route)

/login

## admindetails (after dB::seed)

email : admin@admin.com
password : admin@123


## Project Setup(Web Portal)

### Cloning the GitHub Repository.

Clone the repository to your local machine by running the terminal command below.

```bash
git clone https://github.com/MohYacoub/masterpiece-Mohammad_Yacoub.git
```

### Setup Database

Create your a MySQL database and note down the required connection parameters. (DB Host, Username, Password, Name)

### Install Composer Dependencies

Navigate to the project root directory via terminal and run the following command.

```bash
composer install
```

### Create a copy of your .env file

Run the following command

```bash
cp .env.example .env
```

This should create an exact copy of the .env.example file. Name the newly created file .env and update it with your local environment variables (database connection info and others).

### Generate an app encryption key

```bash
php artisan key:generate
```

### Migrate the database

```bash
php artisan migrate
```

### Send the seeds

```bash
php artisan db:seed
```
