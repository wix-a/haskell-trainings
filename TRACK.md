# Learn a language - Haskell track

### What is Haskell

Haskell is a **general purpose**, statically typed, functional and lazy programming language. It has been gaining much traction in recent years and is known for its glorious compiler, [robust inferred type system](https://softwareengineering.stackexchange.com/questions/279316/what-exactly-makes-the-haskell-type-system-so-revered-vs-say-java/279362#279362) and updated approach to writing code which is:

 { fast, correct, composable, testable } - Choose All

### Why

Haskell brings a different practice to solving problems and fresh ideas about writing code. It's guaranteed to expand your engineering toolbox, thus making you a better developer in any language you're comfortable with.

### How

We will be following Google's open-source Haskell 101 & 102 training material and complete the code labs.

Upon completing this course, you will be able to write simple Haskell programs, interact with the compiler and understand Haskell code examples, which are commonly used to demonstrate most FP related ideas/examples.

### Acknowledgements

- Haskell is not hard, but it is different. Developing intuition about solving a problem with  Haskell requires a paradigm shift, which inevitably takes some time. It's important to get equipped with some patience
- Due to their functional nature, Haskell programs are structured in a manner that makes heavy use of concepts that may be intimidating at first, but have no fear! There's no need to dive into *Category Theory* nor complete all the *Monad* tutorials. These concepts are best understood in practice, when applied to real-world problems (patience, remember?)
- Haskell is not a silver bullet

### What's next

- Upon completing the trainings, we may proceed to the *Data61 Haskell FP-Course* and dive deeper into the Haskell ecosystem
- Learn the *[Stack](https://docs.haskellstack.org/en/stable/README/)* and *[Stackage](https://www.stackage.org)* tool-belt to compose applications with modules and existing open-source libraries
- Use [Hoogle](https://hoogle.haskell.org) - A Haskell API search engine, which allows to search libraries by type signatures
- Deploy a Haskell service

### Prerequisites

Minimal requirements:

- Haskell Stack `brew install stack`
- Text Editor `brew cask install visual-studio-code`
- [Install Haskell Syntax extension](https://marketplace.visualstudio.com/items?itemName=justusadam.language-haskell)

Haskell LSP support (Optional):

- [Haskell IDE engine](https://github.com/haskell/haskell-ide-engine#installation-from-source)
    
    - Add Stack local bin directory to your `$PATH` `export PATH=$PATH:$(stack path --local-bin)`
    - Clone IDE engine `git clone git@github.com:haskell/haskell-ide-engine.git`
    - Install **LTS** (and hoogle docs):

            cd ./haskell-ide-engine
            stack ./install.hs hie-8.4.4
            stack ./install.hs build-doc

    - [Install Language server extension](https://marketplace.visualstudio.com/items?itemName=alanz.vscode-hie-server)

