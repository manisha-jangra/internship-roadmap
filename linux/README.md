# 📘 Linux Journey

## 📌 Project Overview

This repository documents my hands-on learning journey with Linux.  
In this project, I practiced essential Linux commands.

The goal of this project was to understand how linux works in real-world development environments.

---

# 🚀 What I Learned

## 1️⃣ Linux Initialization

```bash
Manisha@DESKTOP-7481ML4 MINGW64 ~
$ cd projects/

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ ls
git-journey/  git-one/  internship-roadmap/

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ pwd
/c/Users/Manisha/projects

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ ls
git-journey/  git-one/  internship-roadmap/

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ ls
git-journey/  git-one/  internship-roadmap/

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ mkdir test-working

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ cd test-working/

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ touch abc.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cp abc.txt
cp: missing destination file operand after 'abc.txt'
Try 'cp --help' for more information.

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cp abc.txt abc.txt
cp: 'abc.txt' and 'abc.txt' are the same file

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cp abc.txt xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
abc.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ rm xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ mv abc.txt xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ uname
MINGW64_NT-10.0-19045

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cd ..

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ locate abc.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ cd test-working/

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ locate abc.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ locate xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ locate xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ touch file.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
file.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ pwd
/c/Users/Manisha/projects/test-working

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ mkdir folder1

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ pwd
/c/Users/Manisha/projects/test-working

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
file.txt  folder1/  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cd folder1

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working/folder1
$ pwd
/c/Users/Manisha/projects/test-working/folder1

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working/folder1
$ rmdir folder1
rmdir: failed to remove 'folder1': No such file or directory

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working/folder1
$ cd test-working
bash: cd: test-working: No such file or directory

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working/folder1
$ cd projects
bash: cd: projects: No such file or directory

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working/folder1
$ cd ..

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ rmdir folder1

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
file.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cp file.txt abc.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
abc.txt  file.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ mv file.txt file1.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
abc.txt  file1.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cd..
bash: cd..: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cd ..

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ mkdir test-working1

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects
$ cd test-working

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ mv file1.txt xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
abc.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ rm abc.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ uname
MINGW64_NT-10.0-19045

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ locate xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ln -s xyz.txt link.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
link.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls -a
./  ../  link.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cat xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ls
link.txt  xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cat xyz.txt
one
Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ ps
      PID    PPID    PGID     WINPID   TTY         UID    STIME COMMAN
     1362       1    1362      11304  ?         197610 22:22:47 /usr/b
     1363    1362    1363      14132  pty0      197610 22:22:47 /usr/b
     1617    1363    1617       1076  pty0      197610 23:21:09 /usr/b

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ man ls
bash: man: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ man touch
bash: man: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ man cp
bash: man: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ grep "one" xyz.txt
one

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "hello"
hello

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "hello world"
hello world

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ pwd^C


Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "hello world" > xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cat xyz.txt
hello world

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ whoami
Manisha

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ sort xyz.txt
hello world

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cat "2" "4" "6" xyz.txt
cat: 2: No such file or directory
cat: 4: No such file or directory
cat: 6: No such file or directory
hello world

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "1"
1

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "2"
2

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "3"
3

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "1" xyz.txt
1 xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "2" xyz.txt
2 xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo


Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "3" xyz.txt
3 xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ sort xyz.txt
hello world

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cat xyz.txt
hello world

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ echo "3" > xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cat xyz.txt
3

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ sort xyz.txt
3

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ cal
bash: cal: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ whereis ls
bash: whereis: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ df -h
Filesystem                                   Size  Used Avail Use% Mounted on
C:/Users/Manisha/AppData/Local/Programs/Git  238G   77G  162G  33% /

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ wc -w xyz.txt
1 xyz.txt

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ wget http://example.com/file.zip%3C/span>
bash: syntax error near unexpected token `newline'

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ wget https://pdfobject.com/pdf/sample.pdf
bash: wget: command not found

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ curl
curl: try 'curl --help' or 'curl --manual' for more information

Manisha@DESKTOP-7481ML4 MINGW64 ~/projects/test-working
$ curl https://pdfobject.com/pdf/sample.pdf
curl: (35) schannel: next InitializeSecurityContext failed: CRYPT_E_NO
_REVOCATION_CHECK (0x80092012) - The revocation function was unable to
 check revocation for the certificate.
 ```