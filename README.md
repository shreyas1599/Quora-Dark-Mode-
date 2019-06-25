# Quora-Dark-Mode-
Dark mode Chrome and Safari extension for Quora

<b>For Chrome<b>:

Dowload only the files listed under ```Chrome``` 
Go to: 
``` 
Chrome > chrome://extensions
``` 

and click on ```Load Unpacked``` and select the ```Chrome``` directory where ever it is stored on your computer.

<b>For Safari<b>:

Download and run on Xcode(if you have it). To allow extensions without a Development Ceritificate to run on Safari, go to:
```
Safari > Preferences > Advanced 
```
and make sure ```Show Develop menu in menu bar``` is enabled. After this, go to:
```
Safari > Develop > Allow Unsigned Extensions 
```
and make sure it is checked.

If you want to make changes to the code, you'll have to manually delete the build folder located at:

```
~/Library/Developer/Xcode/DerivedData
```

Use: 

```
rm -rf ~/Library/Developer/Xcode/DerivedData/<insert-build-folder-name>
```
for the same.

Safari will not run your extension the second time if you don't manually delete the build folder and build it again.
So far, there doesn't seem to be any other way.

Sometimes, Safari uncheks the extension when restarted. Go to:

```
Safari > Safari(in the menu bar) > Safari Extensions 
```
and make sure the extension is selected.
