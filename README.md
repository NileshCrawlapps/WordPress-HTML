# HTML restriction for Wordpress

## For Menu / Navigation

Use the following class for the specified tag.

Main tag ul

```<ul class="metismenu" id="side-menu">```

Inner tag li

```<li class="menu-item"></li>```

Active class

```<li class="menu-item current_page_item"></li>```

Submenu tag ul

```<ul class="submenu metismenu"></ul>```

## For paragraph tag

<b>Avoid using classes on p tags. If you need to style a p tag, use a class on the parent element instead.</b>

## Use the WordPress default body classes to style the body of your page.

- home page  ```class="home ... "```
- blog detail page / any detail page -> ```class="single  ... "```
