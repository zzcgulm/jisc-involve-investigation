# Jisc involve WordPress Twenty Twenty theme investigation

Twenty Twenty is the new default theme for WordPress Version 5.3.
https://wordpress.org/support/article/twenty-twenty/



## Pages

- Home
  - Theme Preview = https://wp-themes.com/twentytwenty/?
  - /
- Page
  - 
    - About = https://wp-themes.com/?page_id=2
    - Parent page = https://wp-themes.com/?page_id=46
  - Sample Page = /sample-page/
- Post
  - Worth A Thousand Words = https://wp-themes.com/twentytwenty/?p=19
  - Hello world! = /2019/11/14/hello-world/
- Category page
  - Category: Uncategorized = https://wp-themes.com/twentytwenty/?cat=1
  - Category: Uncategorized = /category/uncategorized/
- Author page
  - Author: Theme Admin = https://wp-themes.com/twentytwenty/?author=1
  - Author: user = /author/user/
- Archives
  - ?
  - Month: November 2019 = /2019/11/
- Elements
  - Elements = https://wp-themes.com/twentytwenty/?p=36


## Default styles

### Breakpoints

- max-width: 479px
- min-width: 480px
- max-width: 599px
- min-width: 600px
- min-width: 660px
- min-width: 700px
- min-width: 782px
- max-width: 782px
- min-width: 1000px
- min-width: 1220px
- min-width: 1240px
- min-width: 1280px
- min-width: 1330px



## What I know


### Accessibility failures
- Does the "aria-label" attribute accurately describe the element? (A 1.1.1 Non-text Content) = Review: 
  - "Horizontal"
  - "Mobile"
  - These aren't fantastically semantic, especially as this is aimed at screen reader users, who can't see if they are horizontal or on a mobile. But are bearable.
- Link identified only by color (A 1.4.1 Use of Color) = Error: These will be fixed in child theme.
- Link text used for multiple different destinations (A 2.4.4 Link Purpose (In Context) = Error: Nothing we can do about this. #TODO: Report in accessibility statement.



## What I believe is possible


### Customization

- Add a site logo (https://wordpress.org/support/article/twenty-twenty/#site-logo)
- Custom colours (https://wordpress.org/support/article/twenty-twenty/#site-logo)



## Todo

- Work out how to add Roboto font.
- Buttons
- Typography
- Print styles.
