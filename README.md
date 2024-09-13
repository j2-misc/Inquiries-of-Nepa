# Quartz v4

This was built using Quartz v4: https://quartz.jzhao.xyz/.

# Installation
## Dependencies
- Node v20 or higher
- `npm` v9.3.1 or higher

Once all dependencies are installed, in your terminal of choice, enter the following commands:

```
//clone the remote repository
git clone https://github.com/j2-misc/Inquiries-of-Nepa.git

//move into the local repository
cd "Inquiries of Nepa"

//install additional dependencies and set up quartz
npm i
npm audit fix
npx quartz create
```
# Contributing
## WikiLinks
[Obsidian](https://obsidian.md/) and [Quartz 4.0](https://quartz.jzhao.xyz/) both use a system of WikiLinks denoted by two sets of square brackets [[like this]]. This links one page to another by the shortest available path. You should only ever need to use the name of a file to link to it, but Quartz can be a bit finnicky sometimes, so if you have any problems let me know.
## Tags
Tags are a useful way to organize files other than just putting them in folders. Whenever you make a new doc, make sure it has the appropriate tags.
## Pictures
If you're using Obsidian, linking to an image might mess up. As with WikiLinks, you should typically only use the name of the image you're linking to, or else Quartz might break and fail to render the image properly when it's public for everyone to see. So if Obsidian autofills an image link to something like

> `![[public/0---Assets/image.png]]`

replace that stupid link with just

> `![[image.png]]`
## Previewing and Pushing
You can view your local changes by running
> `npx quartz build --serve`

Once you're ready to commit your changes, run
> `npx quartz sync`
