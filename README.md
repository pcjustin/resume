Fork from [David Hamp-Gonsalves](https://github.com/davidhampgonsalves/resume)

I changed CSS formatting what I want to.

# Requirment
Install requirment packages
```
$ npm install
```

Install css
```
$ cp *.css node_modules/markdown-resume/assets/css
```

# Generate resume
```
$ node node_modules/markdown-resume/bin/md2resume resume.md
$ node node_modules/markdown-resume/bin/md2resume --pdf resume.md
```