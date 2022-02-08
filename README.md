# Bootstrap form

This repository contain responsive **Bootstrap** form with inputs, radio buttons, select options, checkbox and textarea. You can use **CDN** for include Bootstrap to your website or [download](https://getbootstrap.com/) it and extract to your local folder, as I use in this case.
So, for all inputs we add label for input fields that match id for input field. This is important for couple of things: user can click on input name to activate it and on mobile devices user can touch name of input to activate it. Also, this is important for screen readers.

For make all inputs, select and textarea 100% of width we add class _form-control_ and for better spacing between each other we make all inputs, checkboxes and textarea inside div class form-group.

For _checkbox_ we wrap input inside label, so that text goes on the right in this case and we put it inside div class checkbox. We have three inputs for checkbox and for make it inline we add class checkbox-inline to labels.

For submit we add classes _btn_, _btn-default_ for determine button use and color, and also we add class _pull-request_ for make it right on the screen.

Heading and footer use class _text-center_ for text-align to the center and also we use some custom style in file **style.css** to add our padding, color, background, position, width and text-decoration.

Also, for input name we add [glyphicons](https://www.glyphicons.com/) icon for success.

[PREVIEW](https://full-stack-web-developer-and-designer.github.io/BootstrapForm/)
