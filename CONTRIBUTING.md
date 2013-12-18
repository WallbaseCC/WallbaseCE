# Contribution Guidelines


## Requirments

1. [Git](http://git-scm.com/downloads)
2. [Composer](http://getcomposer.org/download/)
3. PHPunit (after Composer is installed, run `composer global require 'phpunit/phpunit=3.7.*'`)
4. Some kind of webserver, like [XAMPP](http://www.apachefriends.org/en/xampp.html) that has Apache, PHP and MySQL installed.

## How to contribute

1. Download this repository. `git clone git@github.com:WallbaseCC/WallbaseCE.git`
2. Run `composer update`
3. Find an [issue](https://github.com/WallbaseCC/WallbaseCE/issues) you want to fix.
4. Write a comment there you say "I start working on this". (Necessary so we avoid many people working on the same thing).
5. Start writing code that fix the issue.
6. **Write unit tests that fails without your fix.** Else, what is the point with your fix?
7. Be sure that all unit tests pass.
8. Push your fix! :)
9. Someone will review your fix and accept / deny it