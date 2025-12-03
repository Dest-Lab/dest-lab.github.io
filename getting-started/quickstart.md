---
icon: gear
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
metaLinks:
  alternates:
    - https://app.gitbook.com/s/yE16Xb3IemPxJWydtPOj/getting-started/quickstart
---

# Config file

### Configuration Overview

When you open the Stryde configuration file for the first time\
`~/.config/stryde/config.toml` you will see something like this

```toml
using = "Stryde-Dark"
antialiasing = false
list_text_size = 16
input_text_size = 18
app_width = 774.0
app_height = 500.0
```

#### **using**

Specifies which theme file Stryde should load\
`Stryde-Dark` is the default dark theme

To use your own custom theme, create a toml file in the `themes` folder\
and replace the value with your filename:

```toml
using = "your_theme_name.toml"
```

#### **antialiasing**

Enables smoothing for text and UI elements\
Turning it on may improve visual quality but can reduce performance

#### **list\_text\_size**

Defines the font size for the list of applications

#### **input\_text\_size**

Defines the font size used in text input fields (search bar)

#### **app\_width**

The width of the Stryde window in pixels

#### **app\_height**

The height of the Stryde window in pixels
