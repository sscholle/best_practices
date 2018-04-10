# best_practices
All information regarding best practices for a software project


# CSS/SASS
Please embrace the 'BEM' methodology
> see: https://github.com/sscholle/culture/blob/master/SASS-best-practices.md


In regards to our PHP standards, we've agreed on some definitions for our code formatting that branch off of PSR-2 and extend it.

```PascalCase - To be used for class name definitions

camelCase - To be used for method definitions

snake_case - To be used for variable definitions

ALL_UPPER - To be used for `const` definitions```

Please adhere to these, and follow PSR-4 standards if you're using namespaces

You can find links to the relevant standards here:
https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md


Guys please note that this is no longer okay
```if (statement) {
    // things happen
}
elseif (statement) {
    // or other things happen
}```

The standard and enforced syntax is as follows:
```if (statement) {
    // things happen
} else if (statement) { # note the space and the fact that your else key word is on the same line as the end of your original if
    // other things happen
}```

Also
```$variable= 'value'; // This is not okay
$variable='value'; // This is not okay
$variable ='value'; // This is not okay

$variable = 'value'; // this is okay.```