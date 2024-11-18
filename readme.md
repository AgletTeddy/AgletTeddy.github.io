python3 -m http.server 8080 --bind 127.0.0.1

-   what should we do with the bullet points? they seem weird mainly in desktop

    > > standby

-   links

INFO URLS and Files

-   url FILES work this way

    l-order | p-order | animation/render _ portrait/landscape _ ID \_ R/L . jpg/png/mp4

    thumbnail: animation_portrait_1_R.jpg
    short vid: animation_portrait_1_R.mp4
    full vid: animation_portrait_1_R_full.mp4

    rules for these files a portrait animation, with order # for landscape (desktop) of 1, order # for portrait (mobile) of 2, and for RIGHT TABLE on Desktop case:

    l-1|p-2|animation_portrait_1_R.jpg
    l-1|p-2|animation_portrait_1_R.mp4

    -   only supports jpg/png
    -   ID must be unique and its not used for sorting
    -   when the viewport orientation (mobile VS desktop) is desktop, there are TWO galeries side by side.
    -   the sorting is on URLs file, with d-1|p-2 in the beginning (on desktop, first media, on mobile, second)
    -   that sorting is fundamental to fit everything
    -   to select which gallery to use, RIGHT or LEFT on desktop case, R or L must be present in the end of the file
    -   each animation with its short video needs to have the same name just with .mp4
    -   thumbnail & short-video mp4 MUST BE THE EXACT SAME RESOLUTION
    -   only mp4 is supported
