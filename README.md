# Omni Release Note

## Prerequisite

Clone source code **recursively**
```
$ git clone https://github.com/pangpanglabs/omni-release-note-hugo.git --recursive
Cloning into 'omni-release-note-hugo'...

$ cd omni-release-note-hugo
```

## Deploy

```
$ ./deploy
```

## Development

Install Hugo:
```
$ brew install hugo
```

Live reload:
```
$ hugo server --buildDrafts -w --theme=docuapi
```
Visit http://localhost:1313/omni-release-note/