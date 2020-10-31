# Apos' Theme for VSCode and Sublime Text. Based on Brogrammer and Sapphire.
I use Sublime Text for Competitive Programming and VS Code for Web Development. While doing web development on VS Code, I tried Apos Theme and I liked it very much. Hence, I thought of trying it on Sublime Text 3 also, but unfortunately there was no such package available. Hence, I thought of converting the VS Code theme to Sublime Text Theme. Therefore, on googling, I came across the following repository on googling related stuff:
<a href="https://github.com/tobiastimm/code-theme-converter" target="_blank">Code-Theme-Convertor</a>. You can read more about it in the github repo link. Therefore, using this idea I tried to construct my own Theme using <a href="https://github.com/Apostolique/AposTheme" target="_blank">AposTheme for VS Code</a> and <a href="https://github.com/tobiastimm/code-theme-converter" target="_blank">Code-Theme-Convertor</a> for Sublime Text 3. Unfortunately, CODE_THEME_CONVERTOR has been built only till the idea of making a perfect Color Scheme. Making UI Theme is still in the to-do list.
I saw that the AposTheme uses <a href="https://github.com/kenwheeler/brogrammer-theme" target="_blank">Brogrammer Theme</a>. Hence, I converted the VS Code theme to Sublime Text Color Scheme first using the Code-Theme-Convertor Repo and then I installed Brogrammer theme and used its theme on my Sublime Text.
# PREVIEW FOR VS CODE
### BLUE THEME
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/VS%20CODE_BLUE.png" alt="VsCode Blue">

Colors:
- ![#05070b](https://placehold.it/15/05070b/000000?text=+) `#05070b`
- ![#080d14](https://placehold.it/15/080d14/000000?text=+) `#080d14`
- ![#D2D6DB](https://placehold.it/15/D2D6DB/000000?text=+) `#D2D6DB`
- ![#E74C3C](https://placehold.it/15/E74C3C/000000?text=+) `#E74C3C`
- ![#E67E22](https://placehold.it/15/E67E22/000000?text=+) `#E67E22`
- ![#F1C40F](https://placehold.it/15/F1C40F/000000?text=+) `#F1C40F`
- ![#6C71C4](https://placehold.it/15/6C71C4/000000?text=+) `#6C71C4`
- ![#2ECC71](https://placehold.it/15/2ECC71/000000?text=+) `#2ECC71`
- ![#3498DB](https://placehold.it/15/3498DB/000000?text=+) `#3498DB`
- ![#5C6370](https://placehold.it/15/5C6370/000000?text=+) `#5C6370`

### GRAY THEME
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/VS%20CODE%20GRAY.png" alt="VsCode Gray">

### GREEN THEME
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/VS%20CODE%20GREEN.png" alt="VsCode Green">

### RED THEME
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/VS%20CODE%20RED.png" alt="VsCode Red">

# PREVIEW FOR SUBLIME TEXT:
### BLUE THEME
Theme used (Syntax Specific)=> Brogrammer, Theme used(general):Sunrise, Color Scheme: Apos Blue
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/SUBLIME%20TEXT%20BLUE.png" alt="SUBLIME TEXT BLUE">

### GRAY THEME
Theme used (Syntax Specific)=> Brogrammer, Theme used(general):Brogrammer/Adaptive, Color Scheme: Apos Gray
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/SUBLIME%20TEXT%20GRAY.png" alt="SUBLIME TEXT GRAY">

### GREEN THEME
Theme used (Syntax Specific)=> Brogrammer, Theme used(general):Adaptive, Color Scheme: Apos Green
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/SUBLIME%20TEXT%20GREEN.png" alt="SUBLIME TEXT GREEN">

### RED THEME
Theme used (Syntax Specific): Brogrammer, Theme used(general):Adaptive, Color Scheme: Apos Red
<img src="https://github.com/adipro7/AposTheme-for-Sublime-Text-3/blob/master/docs/SUBLIME%20TEXT%20RED.png" alt="SUBLIME TEXT RED">

To apply such theme, first go through the <a href="https://github.com/tobiastimm/code-theme-converter" target="_blank">Readme.md</a>. Do as it says, run the commands in your terminal. After this is done, a directory named AposTheme will be created in your Home Directory. Go to it. You will see a AposTheme.tmTheme type of file. Actually there is a bug in the above code-converter which converts only the last theme of VS Code to Sublime Text theme when multiple themes are present. So you will have to do that individually. One way is you can fork this repo. Delete the files in themes directory from it and add as and when you need. It works fine then. Copy the entire AposTheme folder to .config->sublime-text-3->packages OR you can go to Sublime Text->Preferences->Browse Packages. Copy the code in <a href="https://github.com/adipro7/AposTheme/tree/master/settings_sublime" target="_blank">settings_sublime_folder</a> folder in the repo. Go to Preferences->Settings. You will see a 2-column window. The left one is a default setting window and cannot be edited. The right one can be edited. So replace the entire code present there by default with the code of <a href="https://github.com/adipro7/AposTheme/blob/master/settings_sublime/settings_general" target="_blank">settings_general</a> file. Edit the code- whichever theme you need just replace the color there. Similarly do for syntax specific themes by copying code from <a href="https://github.com/adipro7/AposTheme/blob/master/settings_sublime/syntax_specific" target="_blank">settings_syntax</a>.
