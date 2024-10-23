# mauiEntryClearBroken

The Entry control on the MainPage.xaml of this project has the property ClearButtonVisibility set to 'Never'.
However, by wrapping the entry in other controls, it is pretty easy to break it again (on Windows).
Simply insert any characters in the Entry and focus it, the Clear 'X' will be displayed anyway.