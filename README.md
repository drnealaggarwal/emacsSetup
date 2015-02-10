Hello there students.

This is the repository for your emacs setup for our Clojure classes. 

To set up your emacs so it looks and behaves just like mine and your fellow students follow these instructions:

1) Close Emacs
2) Delete ~/.emacs or ~/.emacs.d if they exist
3) Run git clone https://github.com/flyingmachine/emacs-for-clojure.git ~/.emacs.d
4) Delete the .emacs.d/.git directory. Create your own git repo for .emacs.d. If you don't know how to use Git please attend one of my Git classes.
5) Create the file ~/.lein/profiles.clj and add the line {:user {:plugins [[cider/cider-nrepl "0.8.1"]]}} to it
6) Open Emacs

That's it!

Now your emacs will look like mine and you'll be able to run Clojure inside it and just GET ON with learning Clojure.