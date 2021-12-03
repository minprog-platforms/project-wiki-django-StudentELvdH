# Application Name

Wiki encyclopedia is an application that alllows for searching, viewing, adding and editing pages (entries) in an encyclopedia called wiki.


## Getting Started

TODO: Describe steps to install requirements and get the application running.

Wiki: Specification 
Complete the implementation of your Wiki encyclopedia. You must fulfil the following requirements:

Entry Page: visiting /wiki/TITLE (a title of an encyclopedia entry): 
    - renders a page that displays content of entry (by calling the appropriate util function);
        - if an entry does not exist --> present an error page "page was not found";
        - if the entry does exist --> present the content of the entry (title of the entry page includes name of entry).

Index Page: update index.html such that:
    - user can click on any entry name to be taken directly to that entry page.

Search: allow the user to:
    - type a query into the search box (to search for an encyclopedia entry):
        - if the query matches the name of an encyclopedia entry: 
            - redirect user to entry’s page;
        - if the query does not match the name of an encyclopedia entry: 
            - show a search results page (displays list of all encyclopedia entries that have the query as a substring); 
                - clicking on any of the entry names --> take user to that entry’s page.

New Page: clicking “Create New Page”:
    - go to a page where user can create a new encyclopedia entry:
        - users can enter a title for the page and, in a textarea, enter the Markdown content for the page.
        - users can click a button to save their new page:
            - if an encyclopedia entry already exists with the provided title, present an error message to user, 
            - otherwise, save encyclopedia entry to disk, and take user to the new entry’s page.

Edit Page (extra): on each entry page:
    - a link to a page where entry’s Markdown content can be edited (in a textarea).
        - textarea is pre-populated with existing Markdown content of the page (i.e. initial value of the textarea).
    - user can click button to save the changes made to the entry; once done redirect user back to entry’s page.

Random Page (extra): clicking “Random Page”:
    - go to a random encyclopedia entry.

Markdown to HTML Conversion: on each entry’s page: 
    - convert any Markdown content in the entry file to HTML (install the python-markdown2 package for conversion via pip3 install markdown2)
    - display to the user




