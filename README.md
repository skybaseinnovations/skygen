SkyGen is a Laravel package designed to streamline your development process. It provides a powerful set of tools to quickly generate CRUD templates based on Skybase's proven template, along with a suite of additional functionalities to enhance your Laravel applications.

## Features
- Rapid CRUD template generation
- Custom Skybase-styled scaffolding
- Additional utilities for common development tasks (more features to be added)

## Installation
- Install the package via composer:


    composer require skybase/skygenflow
  
  
## Usage
After installation, you can use the SkyGenFlow commands to generate your CRUD templates and other components.

## Generating a CRUD Template
    php artisan skygen:crud {ModelName}
    
Replace {ModelName} with the desired name of your model.


## Contributing
Contributions are welcome and will be fully credited. We accept contributions via Pull Requests on Github.

## Pull Requests
- PSR-12 Coding Standard - The easiest way to apply the conventions is to run php-cs-fixer.
- Add tests! - Your patch won't be accepted if it doesn't have tests.
- Document any change in behavior - Make sure the README.md and any other relevant documentation are kept up-to-date.
- Consider our release cycle - We try to follow SemVer v2.0.0.
- Create feature branches - Don't ask us to pull from your master branch.
- One pull request per feature - If you want to do more than one thing, send multiple pull requests.

## Security
If you discover any security-related issues, please email sonaam.hitang@gmail.com instead of using the issue tracker.

## Credits
Your Name
All Contributors
License
The MIT License (MIT). Please see License File for more information.
