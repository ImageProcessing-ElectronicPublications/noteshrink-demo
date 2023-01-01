# NoteShrink demo

### Examples

![examples/graph-paper-ink-only.jpg](examples/graph-paper-ink-only.jpg)  
**83036** bytes

See all imageset [examples](examples).

### [NoteShrink.py](https://github.com/mzucker/noteshrink) (defaul options, post-processing: [Bash-OptImg](https://github.com/BASH-Auto-Tools/bash-optimg))

```shell
noteshrink.py graph-paper-ink-only.jpg 
opened graph-paper-ink-only.jpg
  getting palette...
  applying palette...
  saving page0000.png...
  done

bash-optimg page0000.png 
bash-optimg version 20140329

page0000.png: 13187
  Recompressing IDAT chunks in page0000.png to /dev/shm/optimg.22390.png
   Total length of data found in critical chunks            =     13166
   Best pngcrush method        =   4 (ws 15 fm 0 zl 9 zs 1) =     12446
CPU time decode 0.018145, encode 0.076642, other 0.003684, total 0.108779 sec
 pngcrush: 12446
 optipng: 12076
 advpng: 11198
old size: 13187, new size: 11198 (84%)
```
![output-origin-py/graph-paper-ink-only.jpg.png](output-origin-py/graph-paper-ink-only.jpg.png)  
**11205** bytes

See all imageset [output-origin-py](output-origin-py).

### [NoteShrink-c](https://github.com/ImageProcessing-ElectronicPublications/noteshrink-c) (defaul options, post-processing: [Bash-OptImg](https://github.com/BASH-Auto-Tools/bash-optimg))

```shell
noteshrink graph-paper-ink-only.jpg graph-paper-ink-only.jpg.png
Palette:
0: #e6e6b6
1: #e27b72
2: #607e6d
3: #919684
4: #444541
5: #d74d4d
done

bash-optimg graph-paper-ink-only.jpg.png 
bash-optimg version 20140329

graph-paper-ink-only.jpg.png: 37611
  Recompressing IDAT chunks in graph-paper-ink-only.jpg.png to /dev/shm/optimg.22410.png
   Total length of data found in critical chunks            =     37611
   Best pngcrush method        =   7 (ws 15 fm 0 zl 9 zs 0) =     13629
CPU time decode 0.025724, encode 0.133776, other 0.003645, total 0.172953 sec
 pngcrush: 13629
 optipng: 9515
 advpng: 8743
old size: 37611, new size: 8743 (23%)
```
![output-c/graph-paper-ink-only.jpg.png](output-c/graph-paper-ink-only.jpg.png)  
**8743** bytes

See all imageset [output-c](output-c).
