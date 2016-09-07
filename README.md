# Sencha Themer Demo

An example Ext JS workspace that you can use to try out the Sencha Themer 1.0.

The workspace contains two applications:

 * StarterApp - the standard app that gets generated when you run sencha generate app.
 * FeedViewer - a more complex app multi-tab app that displays data from various news sites and the Sencha forums.

## Requirements

 * Sencha Cmd 6.2
 * Sencha Ext JS 6.2

## Setup

1. Extract a copy of Ext JS 6.2 into a new directory called "ext" in the root of the workspace.
2. Compile and Launch the FeedViewer app:

        cd /path/to/sencha-themer-example-workspace/FeedViewer
        sencha app watch -fashion


Since we're using Fashion, any changes you make to the FeedViewer app using Sencha Themer will immediately be reflected in your browser without reloading. The FeedViewer app should now be available at:

[http://localhost:1841/FeedViewer](http://localhost:1841/FeedViewer)

_Note: If you are running sencha app watch elsewhere, your port may vary.  Check the output of sencha app watch for the correct URL._

## Using Sencha Themer

See the [Sencha Themer Walkthrough](http://docs.sencha.com/themer/guides/walkthrough.html)
