![header](https://capsule-render.vercel.app/api?type=waving&color=1:2F4F4F,150:F5FFFA&height=230&section=header&text=Suh%20Hyeon%20Jun&fontSize=60&reversal=true&section=footer&animation=twinkling&fontColor=F8F8FF&fontAlign=70&fontAlignY=40)
#### DevOps
#### [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSuhHyeonjun&count_bg=%2367CB7D&title_bg=%23544B49&icon=&icon_color=%23FFE2E2&title=%EB%B0%A9%EB%AC%B8%EC%9E%90&edge_flat=false)](https://hits.seeyoufarm.com)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=SuhHyeonjun&show_icons=true&theme=dark)

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

#### SNS
---
[![https://hstory0208.notion.site/About-Me-5ed9944db468458aa3d00e5f7f5ee290](https://img.shields.io/badge/Notion-white.svg?logo=notion&logoColor=black&style=flat)]
[![https://hstory0208.notion.site/About-Me-5ed9944db468458aa3d00e5f7f5ee290](https://img.shields.io/badge/Mail-90EE90?style=flat&logo=naver&logoColor=white)](mailto:guswns0208@naver.com)
[![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:dmsgktn0208@gmail.com)
![instagram](https://img.shields.io/badge/instagram-white.svg?logo=instagram&logoColor=pupple&style=plastic)

![button]<a href="https://hstory0208.notion.site/About-Me-5ed9944db468458aa3d00e5f7f5ee290" target="_blank"><img src="https://img.shields.io/badge/Notion?style=flat-square&logo=000000&logoColor=white"/></a>

![34423](https://img.shields.io/badge/github-GIVEME--STAR-red)

<a href="https://www.instagram.com/hongssup/“><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=Instagram&logoColor=white&link=https://www.instagram.com/hongssup"/></a>

https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white

 <a href="https://hstory0208.notion.site/About-Me-5ed9944db468458aa3d00e5f7f5ee290" target="_blank"><img src="https://img.shields.io/badge/000000?style=flat-square&logo=이미지 이름&logoColor=white"/></a>
 

#### Stack
---
![](https://img.shields.io/badge/mysql-4479A1?style=plastic&logo=mysql&logoColor=white)
![](https://img.shields.io/badge/Javascript-F7DF1E?logo=Javascript&logoColor=black&style=plastic)
![](https://img.shields.io/badge/AWS-FFFAFA?logo=amazonaws&logoColor=black&style=plastic)
![](https://img.shields.io/badge/docker-E0FFFF?logo=docker&logoColor=blue&style=plastic)
![](https://img.shields.io/badge/Github-white?logo=Github&logoColor=black&style=plastic)
![](https://img.shields.io/badge/Terraform-E6E6FA?logo=terraform&logoColor=663399&style=plastic)
![](https://img.shields.io/badge/DevOps-00FA9A?logo=&logoColor=663399&style=plastic)
![](https://img.shields.io/badge/CI/CD-87CEFA?logo=&logoColor=663399&style=plastic)
![](https://img.shields.io/badge/Prometheus-FFE4E1?logo=Prometheus&logoColor=B22222&style=plastic)
![](https://img.shields.io/badge/Grafana-FFFFE0?logo=grafana&logoColor=FF6347&style=plastic)




Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the right
- ✨Magi

## Features

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
