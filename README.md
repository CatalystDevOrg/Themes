# Themes
Official repository containing custom themes for Catalyst
# Submitting Themes
Create a [pull request](https://github.com/CatalystDevOrg/Themes/pulls) adding your theme's CSS file to the repository.
> [!NOTE]
> Make sure your theme is added as a **singular file** in the **root** of the repository
# Catalyst Theme Specification v1
These are the CSS variables to be set for a CTSv1 compatible theme
# Header
It is recommended to put the following information in a comment at the top of the CSS file
- The name of the theme
- The author of the theme
- What version of CTS the theme is supposed to comply with
- Additional credits such as source of the colorscheme or inspiration
# Recommended
Below are the CSS variables that affect the colors of the UI
`primary` - layer 1 color
`secondary` - layer 2 color
`tertiary` - layer 3 color
`userchrome-btn-primary` - primary background color for a button within the userchrome
`userchrome-btn-secondary` - secondary background color for a button in the userchrome **being hovered over**
`button-primary` - primary background color for buttons **not in the userchrome**
`button-secondary` - secondary background color for buttons **not in the userchrome**
`button-tertiary` - tertiary background color for buttons **not in the userchrome**
`foreground` - the color of text and borders
# Optional
These are for more granual control of the IU
`border-radius` - how round elements will be
`tab-radius` - how round tabs will be
`searchbar-radius` - how round the search bar will be
`moremenu-radius` - how round the more menu will be