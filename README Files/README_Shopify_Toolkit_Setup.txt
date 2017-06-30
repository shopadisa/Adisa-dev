This is a readme document detailing the installation of the Shopify Desktop Toolkit.
A indepth version of this installation and command documentation can be found at:
https://shopify.github.io/themekit/

However, we will also outline the installation process here:
1) You can automatically install the Theme Kit with the following command in the terminal:
"curl -s https://raw.githubusercontent.com/Shopify/themekit/master/scripts/install | sudo python"
1.5) You might have to type in your computer password depending on your computer permissions
2) Next, run the command
"theme configure --password=[your-password] --store=[you-store.myshopify.com] --themeid=[your-theme-id]"
in the terminal. Note that the bracketed parts should be replaced with the password, url, and id of the Adisa Shopify. For these entries, please ask administrators for Adisa's information.
3) Lastly, move into the directory that you wish to download these files into and enter "theme download" into the terminal. This will download the current theme and website code.

Note: The terminal commands should be entered without the quotations.