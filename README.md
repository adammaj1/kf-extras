# kf-extras
It is a fork of kf-extras: extras for manipulating output from [Kalles Fraktaler 2](https://en.wikibooks.org/wiki/Fractals/kallesfraktaler) by [Claude Heiland-Allen](https://mathr.co.uk/)
* [original repo](https://code.mathr.co.uk/kf-extras)
* [wikibooks](https://en.wikibooks.org/wiki/Fractals/kf-extras)



# Dependencies
* [OpenMP](https://pl.wikibooks.org/wiki/Programowanie_w_systemie_UNIX/CPU#OpenMP)


# Differences
* here is c, in original C++ ( compile with  g++ -std=c++17  )
* here one file programs ( no other then standard units dependecies ), in original repo there are dependencies


# programs
* expmap




# Git

```
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:adammaj1/kf-extras.git
git push -u origin main
```


## Repo
Settings of remote repo
* in general settings
  * add Social Preview Image ( Images should be at least 640×320px (1280×640px for best display))
* in repository details ( near About) add
  * description
  * website 
  * Topics (separate with spaces) 
  

Locasl repo: 
```
~/Dokumenty/mandelbrot_exp/kfb/g 
```




## Subdirectory

```git
mkdir png
git add *.png
git mv  *.png ./png
git commit -m "move"
git push -u origin main
```
then link the images:

```txt
![](./png/n.png "description") 

```

to overwrite

```
git mv -f 
```



## Github
* [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
* [md cheat sheet](http://mdcheatsheet.com/)
* [CommonMark Spec](https://spec.commonmark.org)
* [Markdown parser ](https://markdown-it.github.io/)

