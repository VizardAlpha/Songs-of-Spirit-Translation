## Translating for Songs of Spirit

To begin, log in to your GitHub account, or if you don't have one yet, create it [here](https://github.com/).

Consult [this list](https://www.science.co.il/language/Locale-codes.php) to find the locale code for your language. Once you've found it, 
head over to the translation bundle folder and check the [list of bundles](https://github.com/VizardAlpha/Songs-of-Spirit-Translation/tree/main/Core/Bundles) that have already been created. 
You're looking for a file called "`bundle_`(insert locale code here)`.properties`". If you don't find one, create one manually (more info below).

#### Editing an existing translation

If a translation bundle already exists, that means someone has already started working on a translation. To edit it or translate text, simply click the file and press the edit (pencil) button in the top right. Once you're done editing, press the green "propose file change" button at the bottom, then "create pull request" (twice).
Once this is done, all you need to do is wait for me to approve your changes.

#### Creating a new translation bundle

If a translation bundle for your language *doesn't* exist, you need to create one yourself.  
In the folder with all the bundles in it, click the *'create new file'* button, and name it `bundle_(locale code here).properties`. 
Then, copy-paste the entire contents of the [English translation bundle](https://raw.githubusercontent.com/VizardAlpha/Songs-of-Spirit-Translation/main/Core/Bundles/bundle.properties) into the file, and translate all the necessary text to your language.
Once you are done, press the *propose new file* button at the bottom, then 'create pull request' twice.  

#### Useful Information

- `#` means comment. Can be useful if you're working on a bundle with a few people to leave information. The game will not read this part of the code.
- Don't use `"` in your translations.
- Respect the rules of grammar in your translations, Capital letters and dots.
- `%s` means an argument that will be replaced when the text is displayed. For example, `Version %s` will replace the `%s` by a string of characters and/or numbers.

#### One more thing
If you think *you can* improve the grammar, syntax,... in the file [bundle.properties](https://github.com/VizardAlpha/Songs-of-Spirit-Translation/blob/main/Core/Bundles/bundle.properties). Edit the file and make a pull request when you think you've finished.


**And that's it.**
