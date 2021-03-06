## echo + go = ecgo

## Enhanced golang version of echo

<br>

### Input from pipe!

```
$ cat << EOF | ecgo -red
> hello world
> testing input from pipe
> EOF
hello world
testing input from pipe
$
```
Of corse it will output in red.


<br>
<br>

Quick Demo:

[![asciicast](https://asciinema.org/a/QzGD4v7g4x4EoQ8YC6BaVztBY.png)](https://asciinema.org/a/QzGD4v7g4x4EoQ8YC6BaVztBY)

<br>
<br>


## Usage:

```
ubuntu@ubuntu:~$ ecgo -help
usage: $ ecgo [OPTION] [OPTION] [OPTION] [MESSAGE]
input from pipe: $ echo "hello world" | ecgo [OPTION] [OPTION]
      -h | -help | --help
            print usage menu)
      -n [MESSAGE]
            no new line
      -r [OPTION] [OPTION] [MESSAGE]
            dont reset the color.
      -s
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

 - On MacOS, the `-white` option appears pink.
 - Does not `error:` an unknown flag.


<br>
<br>

### End README

<br>
<br>


