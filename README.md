Usage
Clone this repo:

    $git clone git@github.com:Shashikant86/MobileDeviceOrientation.git
    $cd MobileDeviceOrientation
Now install Behat, Mink, MinkExtension and their dependencies with composer:

     $ curl http://getcomposer.org/installer | php
This will show you output like this

     $ curl http://getcomposer.org/installer | php
     % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                             Dload  Upload   Total   Spent    Left  Speed
     100 13028    0 13028    0     0   103k      0 --:--:-- --:--:-- --:--:--  189k
     #!/usr/bin/env php
     All settings correct for using Composer
     Downloading...

     Composer successfully installed to: /Users/user/Behat-SauceLabs-Newbie/composer.phar
     Use it: php composer.phar
Notice it has downloaded composer.phar file. You can install it

      $ php composer.phar install
      Loading composer repositories with package information
      Installing dependencies
It will take some time to download all the vendos into you project. Once finished, 'ls' your project it shouls look like this

     $ ls
     README.md  bin       composer.lock   features
     behat.yml    composer.json   composer.phar   vendor
Change 'behat.yml' with your Username and API Key.

Now to launch Behat, to run test on iPhone with Portrait Orientation

      $./bin/behat -p portrait
      
Now to launch Behat, to run test on iPhone with Landscape Orientation

      $./bin/behat -p landscape     
      
Watch The Test running in the SauceLabs.
