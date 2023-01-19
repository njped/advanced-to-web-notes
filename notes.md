# Intro to Web Development
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

---

*ITALICS*

__BOLD__

1. Organized list
2. Ain't it sweet
    1. Hello

* Unorganized List
* Ain't it pretty
    * World

`This is a code snippet`

```
This
is
a
code
block
```

## Development Websites
* mozilla.org
* javascript.info

# Source Code and GitHub

## Git Help for MTEC

1. git status
2. git add < . --all [filename] >
3. git commit -m ""
4. git status to verify
5. git push 

### Branches

1. git branch >> will find out what branch you are in and what branches that have already been created
2. git branch [branchName]
    * git checkout -b [branchName]
3. 


### Merge and Diff
1. git checkout -b [branchName]
2. make changes to files
3. git add and commit
4. git push
5. git merge main
6. git diff main [branchName]

### Merge Errors
* When working with branches make sure to pull before you push your code it helps avoiding merge problemscd 

## Bash Shell
* Bash is a command line shell
    * gives you UNIX commands
    * effciently to run complex tasks
* Dominant shell on UNIX
* The UNIX philosoply
    * Write programs that do one thing and do it well
    * Write programs to work well
    * Write programs to handle text streams
        * because that is a universal interface
* Copying Command
    * `cp -R source_dir target_dir`
    * you can have multiple directories for the source directory even a files will work
* Remove Command
    * rm will permantently remove files
    * rmdir will remove empty directories
    * rm -r will remove directories and everything in it 
        * be careful with this command there is no going back
* Inspect Command
    * -i
        * `rm -ri` will ask you if want to remove directory and files one by one
* You can checkout on commits
    *     do git log to find the unique commit source name to checkout to

# Html and CSS

## Inspecting Code
* be care of overlapping tags in html

## Lists, Tables, Frames and Forms
* Lists
    * `<ul>` -- will use `<li>` to create a nesting list
    * Shortcut
        * `ul>li*3{Itmes$}`
            * `>` means child of the ancestor
            * `{}` means what do you want in the elment
            * `$` numbers the children in order e.x. Items1, Items2, Items3,
* Tables
    * `<thead>` is the header of the tale
        * `<th>` will go in the header of the table
    * `<tbody>`
        * `<td>` will go in the body of the table -- td means table data
    * `<tr>` is row for the table
    * `<td colspan='3'>` -- colapses 3 colums
    * `<td rowspan='2'>` -- colapses 2 rows
    * colgroup example
    ```
    <colgroup>
        <col>
        <col>
        <col>
    </colgroup>
    ```
    * 
* Frames
    * `<iframe>`
* Forms
    * `<input>` and `<label>` are your friends
        * `<input>` has a lot of attributes
            * __*type attribute is really important and has a lot of uses better look up these*__
    * forms work heavily with javascript

## CSS Modules
* Selectors
    * Attributes
        * input[id]
        * [attribute = "value"] // exact string value is "value"
        * [attribute ~= "value"] // space limited
        * [attribute *= "value"] // not space limited
        * Immediate child selector
            * `>`
                * div > p {

                }
        * Descendant selector
            * ` ` space selector
                * div p {

                }
        * Immediate Sibling selector
            * `+`
                * p + span {

                }
        * Non-Imediate Sibling selector 
            * `~`
                * p ~ span {

                }
        * Pseudo Classes
            * :first-child
            * :last-child
            * :only-child
            * nth-child
            * first-of-type
            * last-of-type
* Box Models
    * Flexbox
        * Display: flex -- works only on direct children
    
    Flexbox Guide -- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
    Flexbox Game -- flexbox froggy

* Backgrounds and Borders
    * Background
        ```
        body {
            background-image: url();
            background-size: cover;
            background-repeat: no-repeat;
        }
        ```
    * Positions
        * Static - default position (render in order)
        * Relative
            * You need give position relative and an offset
                * Offset: top, left, bottom, right
            * if you don't do both it will act like a static position
        * Absolute
            * position is very similar to fixed but it's fixed to it's parent/ancestor
        * Fixed
            * Postion is relative to the user's view point
                ```
                bottom: 0px;
                left: 0px;
                ```
            * Fixed position will be at the bottom left
        * Sticky
            * use offsets for positioning but when it leaves offset position it will stick to the top of the screen
                * Ex. Menu bars will sometimes follow the user when they are scrolling the web page
        * Offsets
            * Top
            * Bottom
            * Left
            * Right
            * Width
            * Height
            * Z-Index
                * -1 puts it behind the header or image
                * needs a position 
* Text Effects
    * Colors 
        * rgba (255,255,255,0.5)
            * the .5 is transparentcy this is not like the CSS opacity rule the opacity rule affects the parent and child element but the rgba will only affect the element you are on.
    * Background
        * background-color
        * background-image
        * background-repeat
        * background-attachment
        * background-position
    * Text
        * px - pixels
        * em - industry font size
        * text-align
        * text-decoration: none
        * color
        * font-weight: bold
* Transformations
    * SVG
        * vector graphic designs
* Transitions and Animations

### Cascade Algotithm
1. user agent normal
2. user agent !important
3. user normal
4. author normal
5. css animation
6. author !important
7. user !important

!important overwrite

* Selector Specificity
    1. Inline Style
    2. ID's
    3. Classes
    4. Elements and Pseudo-Elements


# Soft Skills

## Working in a Software Company
* Industry
* Type of Dev Company
* Company Size
* Market (Who are the competitors)
* Users/Customers
* Products/Service

### Questions to ask Myself
* How do software companies get work done?
* What are the different typpes of web developer jobs?
* What Knowledge, Skills & Abilities do you need

### What are THEY Looking for?
* Resume - updating resume to fit the goals or the PLAN of the company

### Searching for Jobs
* Networking
    1. Have neighbors or colleagues to help find jobs that are hiring
    2. Use linkedIn or indeed to network online to show skills that I have
