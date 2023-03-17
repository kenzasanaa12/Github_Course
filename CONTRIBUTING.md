Creating co-authored commits on the command line
Collect the name and email address for each co-author. If a person chooses to keep their email address private, you should use their GitHub-provided no-reply email to protect their privacy.

Type your commit message and a short, meaningful description of your changes. After your commit description, instead of a closing quotation, add two empty lines.

$ git commit -m "Refactor usability tests.
>
>
Tip: If you're using a text editor on the command line to type your commit message, ensure there are two newlines between the end of your commit description and the Co-authored-by: commit trailer.

On the next line of the commit message, type Co-authored-by: name <name@example.com> with specific information for each co-author. After the co-author information, add a closing quotation mark.

If you're adding multiple co-authors, give each co-author their own line and Co-authored-by: commit trailer.

$ git commit -m "Refactor usability tests.
>
>
Co-authored-by: NAME <NAME@EXAMPLE.COM>
Co-authored-by: AUTHOR-NAME <ANOTHER-NAME@EXAMPLE.COM>"
The new commit and message will appear on GitHub.com the next time you push. For more information, see "Pushing commits to a remote repository."

Creating co-authored commits on GitHub
After you've made changes in a file using the web editor on GitHub, you can create a co-authored commit by adding a Co-authored-by: trailer to the commit's message.

Collect the name and email address for each co-author. If a person chooses to keep their email address private, you should use their GitHub-provided no-reply email to protect their privacy.

After making your changes together, at the bottom of the page, type a short, meaningful commit message that describes the changes you made.
Commit message for your change

In the text box below your commit message, add Co-authored-by: name <name@example.com> with specific information for each co-author. If you're adding multiple co-authors, give each co-author their own line and Co-authored-by: commit trailer.

Commit message co-author trailer example in second commit message text box

Click Commit changes or Propose changes.

The new commit and message will appear on GitHub.com.
