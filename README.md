# Marijnworks Utilities  Library

## Disclaimer
This is really some old junk. If there's anything useful in here AT ALL, feel free to just copy. Kudos if you share it publicly and clean things up!


## Installation instructions

Using git as a repository next to packagist is quite simple. Just add this to the bottom of your composer.json file (or add the repository to existing repositories);
```!json
 "repositories": [
    {
        "type": "vcs",
        "url":  "git@bitbucket.org:marijnworks/marijnworks-utilities.git"
    }
]
```

Now, add the Library to the require section as you would with a regular packagist repository:
```
    "Marijnworks/Utilities": "dev-master"
```        

Run composer update and you're done!

## Using the libarary
The classes & their methods should speak for themselves. If not, they might have some in-code comments. 
If  extensive instructions are in place, you should find / put them in the docs folder.


## Requirements / Prequisites
I feel ashamed today I didn't put these in composer back then. But here goes:

* a lot of the classes require curl to be installed
* some require GD or Imagick for Image processing
* the twitterapi requires https://twitteroauth.com/
