# Project "NEASTOR"

# Description
Project NEAStor is a project with an ambitious goal: to provide free access, inspiration and guidance to university, A Level and GCSE students. As you may have guessed, the project was inspired by JSTOR, a digital library of academic resources. Similarly, we aim to provide a digital library of resources for students, but with a twist: we want to provide a platform for students to share their own resources, and to inspire others to do the same. 

NEAStor is a **collection of resources, including subject-specific non-examined assessments (NEAs), coursework, Extended Projects Qualifications (EPQs), university essays, and more**. 

## For Students, By Students
All of the resources on NEAStor are **created by students**. We believe that students are the best people to create resources for other students, as they have recently been through the same process.

# Features

- **Free to use** - NEAStor is completely free to use, and there are no hidden costs or subscriptions.
- **No account required** - You can view resources without creating an account, providing a quick and easy way to find inspiration for your own work.
- **Upload your own resources** - You can upload your own resources to NEAStor, and share them with the world. You can choose whether you want to be credited for your work, or remain anonymous.
- **Revenue sharing** [coming soon] - You can opt-in to revenue sharing, and receive a share of the revenue generated from ads on your resources.
- **Proven grade** [coming soon] - The grades that each resource received is given by the uploader, and is verified by the NEAStor team. This means that you can be sure that the resources are of high quality, and learn from the mistakes of others.
- **For students, by students** - All of the resources on NEAStor are created by students. We believe that students are the best people to create resources for other students, as they have recently been through the same process.

# Usage
## Website
The NEAStor website is available at [neastor.ibaguette.com](https://neastor.ibaguette.com). Pending a full, custom domain name.

## Discord
NEAStor, alongside iBaguette, has a Discord server. You can join the server at [https://discord.gg/GfetCXH](https://discord.gg/GfetCXH).

# FAQ

### Should I use NEAStor?
NEAStor is a great resource for students who are looking for inspiration for their own NEAs, coursework, EPQs, or university essays. It is also a great resource for students who are looking for guidance on how to structure their own work.

### How does NEAStor ensure academic integrity?
There is a strict vetting process for all resources that are uploaded to NEAStor. All resources are checked for plagiarism, and are only uploaded if they are deemed to be original work.

In addition, we do not accept resources for the current academic year. Sharing material, especially NEAs, that are currently being assessed is breaches exam board regulations. 

The earliest resources that we accept are from the previous academic year, and after results day and any disputes have been resolved.

NEAStor shows the end product of the project, not the process. This means that students can use **NEAStor to get inspiration for their own work, but cannot use it to cheat**.

Finally, all material on the site can be indexed by search engines and included in search results. Plagarism in students' work from NEAStor can be detected by plagiarism detection software. In addition, should NEAStor be contacted by a school or exam board regarding suspected plagiarism, we will cooperate fully with the investigation.

### How do I upload my own resources?
To upload your own resources, you must first create an account. Once you have created an account, you can upload your own resources by clicking on the "Upload" button on the top right of the screen. You can then select the file that you want to upload, and add a title and description.

### What about privacy?
For uploaders and content creators, NEAStor allows you to choose whether you want your name to be displayed on the site, and in the material that you upload. If you want to remain anonymous, please remove your name from the material before uploading it! Alternatively, if you want to be credited for your work, you can choose to display your name; this may be beneficial should people want to look up your work, they can find you on social media or other platforms.

For users, NEAStor allows you to view resources without creating an account. We do not store any personally identifiable information about you. For analytics, we use Google Analytics and Cloudflare Insights. Additionally, to fund the site, we use Google AdSense. You can find out more about how Google uses your data [here](https://policies.google.com/technologies/partner-sites). See below for more information.

### Is NEAStor free?
Yes, NEAStor is completely free to use. There are no hidden costs or subscriptions.

### How does NEAStor make money?
NEAStor relies on a small amount of advertising revenue to cover the costs of running the site, hosting resources, improving the services. To do this, we use [Google AdSense](https://www.google.com/adsense/start/).

Please feel free to use an ad blocker if you do not want to see ads on NEAStor. However, please consider whitelisting NEAStor if you find it useful, as this will help us to continue to provide this service for free.

### Can I make money from my resources?
If you have agreed to the Revenue Sharing Agreement, you may be eligible to receive the revenue generated from Google AdSense on your resources, minus a small fee to cover the costs of running the site.

Revenue is calculated based on the number of views that your resources receive in relation to the total number of views on the site. For example, if your resources receive 10% of the total views on the site, you will receive 10% of the revenue generated from Google AdSense on NEAStor.

Please note that ad revenue is not guaranteed and can vary significantly depending on views, ad impressions & clicks, 

This is a new feature, and we are still working on automating the process and making it as transparent as possible! You join the Discord server to find out more.

## Infrastructure

NEAStor is proudly built on iBaguette.com's infrastructure. Please check out their website at [ibaguette.com](https://ibaguette.com) for revision material, teacher resources, and more!

iBaguette is owned and operated by [Draggie306](https://github.com/Draggie306)

### Frontend
The NEAStor frontend (website) is built using [Nuxt.js](https://nuxtjs.org/). 

### Backend
We use a variety of backend services to power NEAStor and reduce costs. These include:
- Flask, a Python web framework, to serve the API
- [Cloudflare](https://www.cloudflare.com/) as a CDN, DNS, DDOS protection, analytics, and more
- [Cloudflare R2 Storage](https://developers.cloudflare.com/r2/) as a storage bucket for resources

### Database
okay okay it's just JSON files right now but we're working on it

### Deployment
The backend is deployed on a Raspberry Pi 5 8GB on my desk. The repo is automatically pulled every 5 minutes, and the server is restarted if there are any changes, available at https://github.com/Draggie306/NEAStor-Server

The frontend is deployed using Cloudflare Pages and updated automatically when there are changes to the repo :D

## API
Coming soon! We aim to have lists of resources available, upload functionality, analytics, and more!

# Contributing
If there's a glaring bug or security issue, please open an issue or contact me on Discord at @draggie. Any other contributions are welcome by opening a pull request.

Please note, if you want to contribute to the resource store, you must go through the upload flow on the website, it can't be done through GitHub.


