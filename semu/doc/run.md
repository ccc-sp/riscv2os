# Run

```
$ make
cc -O2 -Wall -o semu semu.c -lpthread
$ make check
cc -O2 -Wall -o semu semu.c -lpthread
scripts/download.sh
Downloading...
kernel.bin: OK
fs.img: OK
./semu kernel.bin fs.img

xv6 kernel is booting

init: starting sh
$ ls
ls
.              1 1 1024
..             1 1 1024
README         2 2 2059
cat            2 3 25016
echo           2 4 23800
forktest       2 5 13688
grep           2 6 28568
init           2 7 24896
kill           2 8 23752
ln             2 9 23704
ls             2 10 27320
mkdir          2 11 23856
rm             2 12 23840
sh             2 13 43824
stressfs       2 14 24864
usertests      2 15 159064
grind          2 16 39424
wc             2 17 26208
zombie         2 18 23224
console        3 19 0
$ wc README
wc README
45 295 2059 README
$ cat README | grep xv6
cat README | grep xv6
```
