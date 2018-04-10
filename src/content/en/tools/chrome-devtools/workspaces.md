project_path: /web/tools/_project.yaml
book_path: /web/tools/_book.yaml
description: TODO

{# wf_blink_components: Platform>DevTools #}
{# wf_updated_on: 2018-04-10 #}
{# wf_published_on: 2018-04-10 #}

{% include "web/tools/chrome-devtools/_shared/styles.html" %}

# Save Changes To Disk With Workspaces {: .page-title }

{% include "web/_shared/contributors/kaycebasques.html" %}

This guide teaches you how to set up Workspaces. Use Workspaces when you want
to save changes that you make in DevTools to disk.

For example, suppose that you're using DevTools to tweak the CSS of
`example.com`. You have the source code for the site on your Desktop. After
you set up Workspaces, any changes that you make will be saved
to the local files on your Desktop. DevTools subsequently serves the modified
files on your Desktop, rather than going to the network to retrieve the
resources.

## Intended audience for this guide {: #audience }

This guide assumes that you already know how to use DevTools to change CSS.

## Limitations {: #limitations }

Workspaces do **not** work with the following frameworks:

* React
* 

The rest of this section explains why Workspaces don't work with certain
frameworks.

Frameworks use build tools like Gulp and Webpack to transform code from a
structure that is easy for developers to maintain to a structure that is
efficient for consumption on the web (for example, minifying files to remove
unnecessary white space or comments, resulting in less bytes sent over the
network every time a file is requested).

When you make a change in DevTools, 

## When to use Workspaces versus other related features {: #related }

## Set up Workspaces {: #set-up }

1. Click the **Sources** tab.
1. Click the **Filesystem** tab.
1. Click **Add Folder To Workspace**.
1. Select the directory where you are storing your source code.
1. Click **Allow** to give DevTools permission to read and write to this
   directory on your file system.


