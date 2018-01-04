#  linux的删除与创建文件和文件夹
-   ##  删除文件夹  或者文件   rm


参数
-     -f  不提示的删除 
-     -r  递归删除（即删除文件夹下所有文件）
---    
-  ##     创建文件夹  mkdir


参数

-      -p   递归创建文件夹   





```
 mkdir -p  dir/test  
 //创建文件夹dir及其子目录test
```
-      -m   创建文件夹并设置权限
```
       mkdir -m=r-- test
       //创建目录 test 并且设置所有用户只读权限
```

---
-   ##   创建文件  touch 


```

        touch test.txt
        //创建一个test.txt 文件
```





 