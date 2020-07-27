#CATCHAT APP
# Create basic fragments and activities for the app’s contents.
When the user clicks on one of the options in the navigation drawer, we want
to display the fragment or activity for that option. We’ll create the fragments
InboxFragment, DraftsFragment, SentItemsFragment, and
TrashFragment, and activities HelpActivity and FeedbackActivity.
# Create the drawer’s header.
We’ll build a layout, nav_header.xml, for the drawer’s header. It will
contain an image and text.
# Create the drawer’s options.
We’ll build a menu, menu_nav.xml, for the options the
drawer will display.
# Create the navigation drawer.
We’ll add the navigation drawer to the app’s main activity,
and get it to display the header and options. We’ll then
write activity code to control the drawer’s behavior.
# Close the drawer when the user presses the Back button.
If the drawer’s open, we’ll close it when the user clicks on the Back button. If
the drawer’s already closed, we’ll get the Back button to function as normal.
# Test drive the app
When we run the app, a drawer toggle icon is displayed in the toolbar.
Clicking on this icon opens the navigation drawer. When we click on
one of the first four options, the fragment for that option is displayed
in MainActivity and the drawer closes; the option for that item is
highlighted the next time we open the drawer. When we click on one
of the last two options, the activity for that option is started
