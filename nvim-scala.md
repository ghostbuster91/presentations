(Not so) old-school programming using vim

I could never understand why people use vim in the XXI century for coding. Even if we for a moment assume 
that vim is the best text editor on the planet it is only a text editor, and we programmers write code, not text. 
There is a big difference between these two. Code has a structure, it has semantics, and it can have errors and warnings.
Having a better understanding of a code allows tools to provide smart navigation around a codebase.
However, thanks to the creation of some great projects like tree-sitter and LSP these days you can code in almost any editor you want.
During this presentation, I will show you how these tools can work together based on my personal setup with neovim and tell you
why I decided to use it in favor of Intellij Idea, that I have been using for years.


scala variant:
Writing scala outside of Intellij Idea

While this seemed to be impossible a few years ago, it all has changed with the rise of such projects as LSP(metals in our case) and tree-sitter. During this presentation, I will show you how you can build your own IDE for scala based on my nvim setup. We will cover parts that are most essential both from the perspective of writing scala and general software development. We will talk about metals, bloop, lsp, code navigation, making the editor more interactive, and why I decided to use such a setup in favor of Intellij Idea, which I have been using for years.
