## Contracts

This is where we keep, version control and collaborate on improvements to our contracts. Since we created them, they've been used by a few other people.

Most people fork and edit these to suit, but if you find an issue or make an improvement, please do open an issue or submit a pull request, and we'll gladly look at it. 

## Usage

1. You will need Git, Ruby 2 and Bundler installed.

2. Clone the repo:

   ``` 
   $ git clone https://github.com/dxw/contracts.git
   ```
3. Run bundle:
   
   ```
   $ cd contracts
   $ bundle
   ```

   Kramdown should be installed.
   
4. To compile the agreements into HTML:
   
   ```
   $ ./script/compile
   ```

You should find some HTML in the build directory.

## Modification

To make your own agreements, or add a new one, create a Markdown file in the agreements directory. To minimise effort, follow the structure of the existing documents:

```

1. ### A heading

    1. The first item under the heading
    2. The second item under the heading
   
        1. A sub item
        2. Another sub item
        
    3. Back to level two
  
2. ### The next section
```

The Markdown library we're using is Kramdown, because it has a more feature-rich syntax. There's a [quick reference](https://kramdown.gettalong.org/quickref.html) if you need it.
