# Metadata-302 Redirecting

Create a redirect link that shows special information when sharing a url and **Redirecting to a 3rd party, attaching metadata to the reference**. 

In order for this to work, the **redirect script must be in the footer!**

### Why in the Footer tag?

In order for the link reference (such as Facebook, Twitter, Text link) to load the appropriate information, it needs to read the metadata before reading the JavaScript Redirect Execution.

This means the information (Metadata) will remain in the ***< header > </ header >*** tags.
