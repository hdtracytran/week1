# String Length and Indexing

This assignment has starter code (in `welcome.c`) that will print the `strlen` of the first command-line argument (expected to be a name).

Your task is to add another print statement that prints the first character of that name, so that the full output looks like this:

```
$ clang welcome.c -o welcome
$ ./welcome Joe
Hi Joe, your name is 3 characters long according to strlen.
The first character of your name is J
```

## Exploration

Once you get that working, you can commit and push from the Codespace, and see your grade (check out the video for details).

After you've confirmed your solution works, see what the program does with _your_ name.

Then, try these explorations:

- Use a name with multiple parts, like `Joe Politz`. Try it both with and without quotes:

  `./welcome Joe Politz`
  
  `./welcome 'Joe Politz'`
- Try the name `José`
- Try the name `Ülo`
- Try the name `李` (the [Chinese surname Li/Lee](https://en.wikipedia.org/wiki/Li_(surname_%E6%9D%8E)))

(If you don't know how to type those characters, you can copy-paste from this README!)

What do you get as output? Edit this README file by copy-pasting or screenshotting the output you got, what you expected to see, and why there is a difference (if any).

(You can edit the README file in your codespace or on github.com).

Add your answers here:

- ./welcome Tracy --> first character is still T, 5 characters
- ./welcome 'Tracy Tran' --> first character is still T, 10 characters
- ./welcome José --> first character is J, 5 characters including the accent mark
- ./welcome Ülo --> first character is 'unknown', 4 characters long
- ./welcome 李 --> first character is 'unknown', 3 characters long
