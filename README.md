# tableau-php-api
PHP Library for using Tableau REST API

## Installation
composer require 'rajvantchahal\TableauAPI';

## Usage

require 'vendor/autoload.php';

use rajvantchahal\TableauAPI\TableauAPI;

$tableauAPI = new TableauAPI('URL, 'USERNAME, 'PASSWORD, 'SITENAME);

$login = $tableauAPI->signIn();
