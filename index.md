## Lets' go

My first topic to review is Privilege Escalation in Linux, here I leave several interesting links with a lot of content about it.

[1](https://github.com/TCM-Course-Resources/Linux-Privilege-Escalation-Resources)
[2](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md)
[3](https://github.com/sagishahar/lpeworkshop)
[4](https://mil0.io/linux-privesc/)
[5](https://vulp3cula.gitbook.io/hackers-grimoire/post-exploitation/privesc-linux)
[6](https://github.com/m0nad/awesome-privilege-escalation#sudo-and-suid)
[7](https://book.hacktricks.xyz/linux-unix/privilege-escalation)

I don't speak or write in english but I will try.
To improve that point I am taking English classes.
I must confess that sometimes it's exhausting :) because of my level is not fluent at all. 

My teacher is [Javiera_Montero](https://www.instagram.com/emi_jvmo/)

### Notes

The following commands correspond to the enumeration process 

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

# Enumeration


uname -a
hostname
cat /proc/version
cat /etc/issue
lscpu
ps aux  
ps aux | grep root


# User Enumeration
 

whoami
id
sudo -l

cat /etc/passwd
cat /etc/shadow


------------------------------------------

# Search SUID 

find / -perm -u=s -type f 2>/dev/null
find /* -user root -perm -4000 -print 2>/dev/null
find / -perm -g=s -type f 2>/dev/null

# Search capabilities 

getcap -r / 2>/dev/null

# Search sudo

sudo -l


1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/hhhj4ns/hhhj4ns.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
