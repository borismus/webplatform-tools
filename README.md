# Command line tools for the webplatform.org project

Get a directory listing of all things under a specified prefix:

    wpd ls <prefix>

Replace a specific page:

    wpd edit <page> <content>


# Not implemented yet

Replace a section in a specified page

    wpd edit <page> -s <section> <content>

Stdin versions of editing for convenience

    echo "<page content>" | wpd replace <page>
    cat <content file> | wpd replace <page> -s <section>

Modify flags

    wpd flag <page> <flag>
    wpd flag -d <page> <flag>

Get an oDesk worker to improve a particular page on the wiki.

    wpd odesk-fix <page> -i <special instructions>
