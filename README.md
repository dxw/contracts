## Contracts

This is where we keep, version control and collaborate on improvements to our contracts. 

It is plausibly not of general interest! But if you'd care to open an issue or submit a pull request, we'll gladly look at it. And if you're running a similar business and would like to fork the repo, you're more than welcome to do so.

## Uage

1. Clone the repo:

   ``` 
   $ git clone https://github.com/dxw/contracts.git
   ```
2. Run bundle:
   
   ```
   $ cd contracts
   $ bundle
   ```

   Kramdown should be installed.
   
3. To compile the agreements into HTML:
   
   ```
   $ bundle exec ./compile
   ```

You should find some HTML in the build directory. This tool is a bit rough & ready, and we probably won't spend much time improving it, but do raise an issue if it just doens't work at all.

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

The Markdown library we're using is Kramdown, because it has a more feature-rich syntax. There's a [kramdown.gettalong.org/quickref.html](quick reference) if you need it.
