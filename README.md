#PSR-1 and PSR-2 changes

It's a simple modification of the PSR-1 and PSR-2 conding standards. 
I welcomed this new idea of having a good PHP coding standard used by many programmers. Unfortunatelly, I can't get used to the "same line opening braces" for control structures. 
I am bothered by the fact that opening braces for classes and functions MUST go on the next line but in this case they have to be in the same line. 

Differences
----------------
- opening braces for control structures MUST go on the new line
- else elseif are on the next line as the closing brace from the earlier body
- catch and finally are on the next line as the closing brace from the earlier body
- do-while, while is on the next line as the closing brace from the earlier body
- that's all :)
 
Examples
----------------
```php
<?php
if ($expr1) 
{
    // if body
} 
elseif ($expr2) 
{
    // elseif body
} 
else 
{
    // else body;
}
```

Issues
----------------
Doing some changes the following packages that follow these standards
- [FriendsOfPHP/PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

