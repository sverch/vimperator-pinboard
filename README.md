# Vimperator plugin for pinboard.in

Plugin to add commands to vimperator that will save bookmarks to pinboard.in.

# Usage

    :pin[board] [-s] [-r] [-d <description>] [-n <notes>] [space separated tags]...
        -s Bookmark as public.  Default is private.
        -r Bookmark as read.  Default is unread.
        -d Set the description (title) of the bookmark.  Default is the current buffer's title.
        -n Set the notes (description) of the bookmark.  Default is the currently selected text.

# Disclaimer

I did not write this, but as far as I know I'm the first person to create a dedicated repo for it.
There's a random gist [here](https://gist.github.com/anonymous/ebd945b74e758d19591c), with usage for
it [here](https://notes.pinboard.in/u:lawren/8298288303f46af2fde3), but the version in this
repository was actually taken from
[here](https://github.com/jothirams/vromerc/blob/master/vimperator/plugin/pinboard.js).  Feel free
to contribute if you use it!
