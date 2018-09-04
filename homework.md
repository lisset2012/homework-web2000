Homework
Answer the following questions:
    1. How do we measure the length of the critical rendering path? (10 pts)
        1. The number of server round trips your page must do in order to fully load and render
        2. The number of actions the browser must take (eg run js, build cssom, build dom, etc) in order to fully load and render your page
        3. By counting the number of all external resources that must be loaded
        4. By counting the number of render-blocking external resources that must be loaded

            Answer: No2

    2. What are the events in the Timeline pane which show the DOM being built, the CSSOM being built, and the render tree being built? (10 pts)
        1. Parse HTML, Parse CSS, Layout
        2. Parse HTML, Recalculate Style, Layout
        3. Parse HTML, Recalculate Style, Paint

            Answer: No1

    3. What is the render tree? (10 pts)

             Answer: Is the combination of the CSSOM tree and the DOM tree.

    4. What are three things you can do in order to speed up a website's load time? (10 pts)

            Answer:
                1. Minify and combine files
                2. Enable browser caching
                3. Reduce image sizes

    5. What is the name of the Google tool you can use to see a list of things you can do to improve your page's load speed? (10 pts)

            Answer: PageSpeed

    6. What is the purpose of including multiple <source> elements within a single <video> element?

            Answer: So the content is can be supported across all major browsers.

    
