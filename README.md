# docker-kali-x11

Use `docker build -t mykali . --no-chace` build image.

Use `docker run -it -p 12345:22 mykali` running container,port 12345 can defined by self.

When connect with mobaxterm by ssh,tpye `xhost +`to use gui.
you can install [metapackages](https://www.kali.org/docs/general-use/metapackages/),recommand `apt install kali-linux-default`.
