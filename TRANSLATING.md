## Translating for Necesse

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

- `//` means comment. Can be useful if you're working on a bundle with a few people to leave information. The game will not read this part of the code

#### Testing your translation bundle

There are one way to test the translation bundle:
1) Assuming you have the game downloaded, download your bundle file, then place it in the same folder as the Songs of Syx `` and run it.

**And that's it.**  

*(...of course, that's never really it. Bother me on Discord when something inevitably goes wrong.)*
