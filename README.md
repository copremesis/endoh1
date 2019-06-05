![](ascii-fluid.gif)

# original video

https://www.youtube.com/watch?v=QMYfkOtYYlg

# original code is here:

http://ioccc.org/2012/endoh1

when attempting this command:

`wget -r http://ioccc.org/2012/endoh1/`

it would grab a slew more projects. 

Instead I pushed it to this repo and even made a docker
to make life easier for those interested in studying this
sort of stuff. 


# docker repo

```bash
git pull copremesis/ascii-fluid
docker run -it -w /root/endoh1 copremesis/ascii-fluid bash
```

