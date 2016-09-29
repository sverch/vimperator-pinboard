# Vimperator plugin for pinboard.in

Plugin to add commands to vimperator that will save bookmarks to pinboard.in.

# Usage

    :pin[board] [-s] [-r] [-t <title>] [-d <description>] [space separated tags]...
        -s Bookmark as public.  Default is private.
        -r Bookmark as read.  Default is unread.
        -t Set the title of the bookmark.  Default is the current buffer's title.
        -d Set the description of the bookmark.  Default is the currently selected text.

# Disclaimer

I did not write this, but as far as I know I'm the first person to create a dedicated repo for it.
There's a random gist [here](https://gist.github.com/anonymous/ebd945b74e758d19591c), with usage for
it [here](https://notes.pinboard.in/u:lawren/8298288303f46af2fde3), but the version in this
repository was actually taken from
[here](https://github.com/jothirams/vromerc/blob/master/vimperator/plugin/pinboard.js).  Feel free
to contribute if you use it!
