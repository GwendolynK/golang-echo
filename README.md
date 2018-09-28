## echo + go = ecgo

## Enhanced golang version of echo

[![asciicast](https://asciinema.org/a/d6oY0Iv0cdFz43SXMuzTwiGmH.png)](https://asciinema.org/a/d6oY0Iv0cdFz43SXMuzTwiGmH)

<br>
<br>


## Usage:

```
ubuntu@ubuntu:~$ ecgo -help
usage: $ ecgo [OPTION] [OPTION] [OPTION] [MESSAGE]
      -h | -help | --help
            print usage menu)
      -n [MESSAGE]
            no new line
      -r [OPTION] [OPTION] [MESSAGE]
            dont reset the color.
      -s [OPTION] [OPTION] [MESSAGE]
            resets the color output.
      -e [OPTION] [MESSAGE]
            use the \ options,
            eg. $ ecgo -e "your message"
      -f | -force [MESSAGE]
            force print message, even if its -help
      -red [MESSAGE]
            print message in givin color
      -yello [MESSAGE]
            print message in givin color
      -green [MESSAGE]
            print message in givin color
      -blue [MESSAGE]
            print message in givin color
      -white [MESSAGE]
            print message in givin color
      -teal [MESSAGE]
            print message in givin color
      -i | -info | --info
            print script info
      -v | -version | --version
            print script version)
Source code: https://github.com/WestleyK/golang-echo

ubuntu@ubuntu:~$ 
```


<br>
<br>


## Known bugs:

 - on MacOS, the `-white` option appears pink.
 - dose not `error:` on unknown flag.


<br>
<br>

### End README

<br>
<br>


