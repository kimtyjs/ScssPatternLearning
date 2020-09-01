# ScssPatternLearning


As we can see, everything is in a big sass directory. At the top-level of the directory is a single main.scss file (this is the input file) and seven subdirectories:

    abstracts contains no actual styles, just Sass mechanisms that help define styles in other directories (sometimes called "helpers"). This includes things like global variables, functions, and mixins. Each of these categories should be placed in their own appropriately-named partial file, as seen above.

    vendors contains any third-party stylesheets a project uses. For instance, if we wanted to use Bootstrap alongside our own custom Sass in a project, we'd download the Bootstrap stylesheet and place it here.

    base contains boilerplate used throughout an entire si te. This includes project-wide typography styles, and stylesheets that universally reset or normalize default CSS.

    layout contains styles for different aspects of the site's structural layout (think of areas like nav bars, headers, footers, etc.)

    components are like "mini" layouts. Styles for small, reusable pieces of the site should reside here (think buttons, forms, profile pictures, etc.)

    pages is where page-specific styles reside. For instance, if a project contained several style rules that are only ever used on the "Contact Us" page, they'd live here in a _contact.scss file, as seen above.

    themes is used whenever a site has multiple themes. For instance, the example project above includes both admin and default themes. We can therefore assume this example site is styled entirely differently for logged-in admins. Perhaps to better present and accommodate the additional features an Admin has. Some websites also offer a "night mode", where the background of the site is darker with lighter-colored text for easier reading in low-light environments. An option like this would be represented in its own theme file too.
