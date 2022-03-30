# docker-kali-x11

Use `docker build -t mykali . --no-cache` build image.

Use `docker run -it -p 12345:22 mykali` running container,port 12345 can defined by self.

When connect with mobaxterm by `ssh root@127.0.0.1 -p 12345`,tpye `xhost +`to use gui.

you can install [metapackages](https://www.kali.org/docs/general-use/metapackages/),recommand `apt install kali-linux-default`.
