{
  "title": "This Site",
  "date": "2021-08-17T16:14:49-05:00",
  "image": "/img/projects/this-site.png",
  "link": "https://github.com/grygon/jrubin.me",
  "description": "The implementation of this website. Utilizing a customized Hugo template as its base, with customization and a CI/CD pipeline for automatic deployment",
  "tags": ["WebDev","GitLab CI/CD","HUGO","SysAdmin"],
  "fact": "",
  "featured":true
}

This site was implemented using HUGO from [an open source theme](https://github.com/eddiewebb/hugo-resume).
A number of tweaks were applied to end up with a final product that I'm happer with. Most notably, there have been some minor tweaks to the main page and projects page, and much of the framework for the Skills section was revamped.
The site is hosted on GitHub, and is automatically being deployed to my webserver via GitHub Actions.
One of the great joys of this being a static site is that I can use Cloudflare to ensure nearly zero load on my web host, as well as near-100% uptime.
