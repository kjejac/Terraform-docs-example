# Writing Good Documentation

## Step 1 - Using Codeblocks
Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.
In order to create codeblocks you need to use three backtics ( ``` ) before and after.
Not to be confused with single quotations ( ''' ).

```
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, World!");
    }
}
```

When you can you should attempt to apply syntax highlighting to your codeblocks

``` c#
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hello, World!");
    }
}
```
Absolute path
![image](https://github.com/kjejac/Terraform-docs-example/assets/77548406/09a686d0-ea36-4024-9a85-f81f26d787cd)

Link to image in repo, dynamic 

![Uploaded image to Github](assets/24893_114858655200558_6859128_n.jpg)

*Use HTML width to edit the size of the picture*

<img width="200px" src="https://github.com/kjejac/Terraform-docs-example/assets/77548406/09a686d0-ea36-4024-9a85-f81f26d787cd">


Code with error
``` C#
class Program
{
    static void Main()
    {
        string message = null;
        Console.WriteLine(message.Length);
    }
}
```
> Error from console, use **Bash** for the codeblock
``` Bash
Unhandled exception. System.NullReferenceException: Object reference not set to an instance of an object.
   at Program.Main() in C:\path\to\your\file\Program.cs:line 7
```
## Step 3 - Use Github Flavoured Markdown Task Lists
Github etends Markdown to have a list where you can check off items [<sup>[1]</sup>](#external-references)

- [X] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

Github Flavoured Markdown (GFM) supports emoji shortcodes. Here are som examples:[<sup>[2]</sup>](#external-references)
|Name|Shortcode|Emoji|
|---|---|---|
|Clouds|`:cloud:`|☁️|
|Cloud with lightning|`:cloud_with_lightning:`|🌩️:

## Step 5 - how to create a table

You can use the following markdown format to create tables:

```md
|Name|Shortcode|Emoji|
|---|---|---|
|Clouds|`:cloud:`|☁️|
|Cloud with lightning|`:cloud_with_lightning:`|🌩️|
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sup>[3]</sup>](#external-references)
>

## Step 6 - Footnotes
Something something more something[^1]


## External References
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [GFM - Taskslists](https://github.github.com/gfm/#task-list-items-extension-) <sup>[1]</sup>
- [GFM - Emoji CheetSheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) <sup>[2]</sup>
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[3]</sup>
- [Footnote](^1)












