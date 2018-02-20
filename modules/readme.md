### Items
This table describes what features are used in the theme and where to find them. Respectively, there is a reverse, module-based list below.

| Feature          | Module                  | Hint                                             |
|------------------|-------------------------|--------------------------------------------------|
| __Locations__    |                         |                                                  |
| `Options_Page`   | Core                    | Used for theme options                           |
| `Post_Type`      | [`events`](events), [`content-blocks`](content-blocks)  | Adds meta boxes to pages and events.             |
| `Taxonomy`       | [`enhanced-categories`](enhanced-categories)     | Displays the fields when adding and creating categories. |
| `Comment`        | [`comment-tags`](comment-tags)            | Renders the field when editing a comment.        |
| `User`           | [`photographers`](photographers)           | Displays the copyrights link field for every user. |
| `Widget`         | [`accordion`](accordion)               | Handles the widget.                              |
| `Menu Item`      | [`menu`](menu)                    | Displays additional fields in menu items.        |
| `Attachment`     | [`photographers`](photographers)           | Handles the photographer field for images.       |
| `Customizer`     | [`site-layout`](site-layout)             | Shows a new section in the Customizer.           |
| `Shortcode`      | [`shortcode`](shortcode)               | Allows the addition of quotes with extra styles. |
| __Fields__       |                         |                                                  |
| Text             | quote, accordion-widget | Used for the author, title and etc.              |
| Map              | events                  | Used to set the location of events.              |
| Sidebar          | menu                    | Used to select a sidebar for mega-menus.         |
| Text             | team                    | Used for team member names                       |
| Checkbox         | events                  | Checks if the event is physical or not.          |
| File             | downloads               | Allows a downloadable file to be assigned to posts. |
| Object           | content-blocks          | Used for the teaser block.                          |
| Tab              | site-layout             | Used to toggle between layout and background.    |
| Date             | events                  | Used to select the beginning and end of events.  |
| Complex          | content-blocks          | Used for displaying buttons.                     |
| Textarea         | accordion-widget        | Allows the content of individual sections to be entered. |
| Image            | site-layout             | Handles the page background in boxed mode.       |
| Objects          | related-posts           | Used to select the related posts.                |
| Section          | events                  | Separates the date fields and the location.      |
| Repeater         | team                    | Used to add departments and teams to the team page. |
| WYSIWYG          | content-blocks, team    | Used for the individual team-member bios.        |
| Select           | site-layout             | Lets you select which site layout to use.        |
| Audio            | content-blocks          | Audio files selection.                           |
| Link             | photographers           | Allows the entry of copyright links for users.   |
| Message          | colors                  | Indicates the availability of the module in the customizer. |
| Layout           | content-blocks          | Works as the base of the blocks field.           |
| Password         | -                       | Although the field is simple, examples must be too complex. |
| Multiselect      | comment-tags            | Allows the selection of related tags for the comment. |
| Color            | colors, enhanced-categories | Picks the color of the site accent or category. |
| Font             | fonts                   | Allows the selection of a body font.             |
| Gallery          | content-blocks          | Handles the "Gallery" block.                     |
| Image Select     | colors                  | Allows the use of a pre-defined color.           |
| Icon             | content-blocks, menu    | Used in the Text content block and for menu icons. |
| Video            | content-blocks          | Used in the "Video" block.                       |
| Map              | events                  | Selects the location of the event.               |
| Embed            | content-blocks          | Main handler of the embed block.                 |
| Sidebar          | menu                    | Allows the dropdown sidebar selector to work.    |
| Number           | enhanced-categories     | Controls the amount of posts per page on the listing. |

### Modules
Modules group different examples together and use the hooks in the base to display and add their content. Each module has a readme in its own directory, which describes what features are used and what is being done there.

- [`content-blocks`](modules/content-blocks): Replaces the content editor of pages with a layout field.
- [`events`](modules/events/): Creates a new post type for events, featuring dates, maps and the `Post_Type` location.
- [`menu`](modules/menu/): Showcases the usage of the `Menu_Item` location with custom sidebars and icons.
- [`quote`](modules/quote/): Showcases the usege of the `Shortcode` location to add a shortcode for a quote.
- [`related-posts`](modules/related-posts/): Adds fields for other related posts to post edit screens.