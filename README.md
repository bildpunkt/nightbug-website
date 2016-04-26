# Nightbug

This is the repository containing all data needed to build the website for Nightbug

## Development

### Requirements

* Ruby
* Jekyll

If both of these dependencies are installed you can just run `jekyll build` to compile the lastest version of the website into the `_site` folder.

## How member data works

Each member is listed in `_data/members.yml`, this section will explain what you need to fill out where to get it working without any problems:

```
- username: "username" // your username
  title: "title" // your profession, tagline, whatever fits your needs
  description: "description" // a short description about you
  skills: // list up some skills of yours
    - "just"
    - "a"
    - "list"
  website: "http://example.com" //your website (with protocol please)
  github: "username" // your Github username
  twitter: "username" // your Twitter username
  avatar: "image.png" // your profile picture (place in /assets/img/members/ )
  background: "http://example.com/example.png" // (panel background image, please add URL here, upload to imgur or somewhere else)
```