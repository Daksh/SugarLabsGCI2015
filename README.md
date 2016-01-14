# Sugar Labs GCI Site 2015/16

##Adding Mentors/Students to the list

1. In the `_data` directory, open the mentors.yml or the students.yml for whichever one needs to be changed.
2. At the end of a file, create a new block with the following information
 ```
 - name: 
  github: 
  image: 
  blog:
  twitter:
  facebook:
  stackexchange: 
  bio:
  ```
3. Add all the information that is available and feel free to leave the lines for which information is not present.
4. For adding the image, just add the image name with the extension like `daksh.jpg` and add that image in the `img/mentors` or the `img/students` directory.


Testing this

[![Build Status](https://travis-ci.org/fossasia/gci15.fossasia.org.svg)](https://travis-ci.org/fossasia/gci15.fossasia.org)


## Run this website on Github
Fork this repo, and it should be on `http://<username>.github.io/gci15.fossasia.org` now.

## Running the website on Local Machine
### Clone Repo

    git clone https://github.com/fossasia/gci15.fossasia.org.git

or own fork version

    git clone https://github.com/<username>/gci15.fossasia.org.git

### Install Jekyll

    gem install bundler
    gem install github-pages

*Use sudo if there is any permission issue*

### Running website

    cd gci15.fossasia.org
    jekyll serve
    
### Go to

    http://0.0.0.0:4000/ or http://localhost:4000/

## Useful Git Tricks
  see [GIT.md](https://github.com/fossasia/gci15.fossasia.org/blob/gh-pages/GIT.md) 

## Demo

You can see the current website [over here](http://gci15.fossasia.org).
