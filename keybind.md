# ncdc Keybinds list

## Key bindings for: global - Global key bindings.

Alt+j        Open previous tab.
Alt+k        Open next tab.
Alt+h        Move current tab left.
Alt+l        Move current tab right.
Alt+a        Move tab with recent activity.
Alt+<num>    Open tab with number <num>.
Alt+c        Close current tab.
Alt+n        Open the connections tab.
Alt+q        Open the download queue tab.
Alt+o        Open own file list.
Alt+r        Refresh file list.

## Keys for tabs with a log window:
Ctrl+l       Clear current log window.
PgUp         Scroll the log backward.
PgDown       Scroll the log forward.

Keys for tabs with a text input line:
Left/Right   Move cursor one character left or right.
End/Home     Move cursor to the end / start of the line.
Up/Down      Scroll through the command history.
Tab          Auto-complete current command, nick or argument.
Alt+b        Move cursor one word backward.
Alt+f        Move cursor one word forward.
Backspace    Delete character before cursor.
Delete       Delete character under cursor.
Ctrl+w       Delete to previous space.
Alt+d        Delete to next space.
Ctrl+k       Delete everything after cursor.
Ctrl+u       Delete entire line.

## Key bindings for: browse - File browser.

Up/Down      Select one item up/down.
k/j          Select one item up/down.
PgUp/PgDown  Select one page of items up/down.
End/Home     Select last/first item in the list.
/            Start incremental regex search (press Return to stop editing).
,/.          Search next / previous.
Right/l      Open selected directory.
Left/h       Open parent directory.
t            Toggle sorting directories before files.
u            Toggle sorting unknown files before files existing locally.
s            Order by file size.
n            Order by file name.
d            Add selected file/directory to the download queue.
m            Match selected item with the download queue.
M            Match entire file list with the download queue.
a            Search for alternative download sources.

## Key bindings for: connections - Connection list.

Up/Down      Select one item up/down.
k/j          Select one item up/down.
PgUp/PgDown  Select one page of items up/down.
End/Home     Select last/first item in the list.
d            Disconnect selected connection.
i/Return     Toggle information box.
f            Find user in user list.
m            Send a PM to the selected user.
q            Find file in download queue.
b/B          Browse the selected user's list, B to force a redownload.


## Key bindings for: queue - Download queue.

Up/Down      Select one item up/down.
k/j          Select one item up/down.
PgUp/PgDown  Select one page of items up/down.
End/Home     Select last/first item in the list.
K/J          Select one user up/down.
f            Find user in user list.
c            Find connection in the connection list.
a            Search for alternative download sources.
d            Remove selected file from the queue.
+/-          Increase/decrease priority.
i/Return     Toggle user list.
r            Remove selected user for this file.
R            Remove selected user from all files in the download queue.
x            Clear error state for the selected user for this file.
X            Clear error state for the selected user for all files.

Note: when an item in the queue has `ERR' indicated in the
priority column, you have two choices: You can remove the
item from the queue using `d', or attempt to continue the
download by increasing its priority using `+'.


## Key bindings for: search - Search results tab.

Up/Down      Select one item up/down.
k/j          Select one item up/down.
PgUp/PgDown  Select one page of items up/down.
End/Home     Select last/first item in the list.
f            Find user in user list.
b/B          Browse the selected user's list, B to force a redownload.
d            Add selected file to the download queue.
h            Toggle hub column visibility.
u            Order by username.
s            Order by file size.
l            Order by free slots.
n            Order by file name.
m            Match selected item with the download queue.
M            Match all search results with the download queue.
q            Match selected users' list with the download queue.
Q            Match all matched users' lists with the download queue.
a            Search for alternative download sources.


