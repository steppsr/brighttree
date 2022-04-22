# Building a Chia Dashboard on Linux - A Walkthrough #

<img width="800" src="https://brighttreedashboard.com/assets/dashboard_screenshot.png" />

I got started with Chia back in early April 2020. While I was familar with Linux, I wasn't a daily user and didn't know Bash that well. Over the months since then, I've slowly put together a series of Bash scripts that are basically the backend for a PHP dashboard application for Chia. This post will walk through the steps to build your own on Linux from scratch. 

**Note**: I built this dashbaord for my farm and as a learning experience for Linux & Bash. All my plots are in one NFT and I am in [Space Pool](https://pool.space). I am also co-farming the fork [HHDcoin](https://hddcoin.org). You may need to make adjust for your configuration.

Warning: This Walkthrough is long. Very long. But I think it's fun, hopefully you will too. Even if you don't build the dashboard, you may find it interesting to browse some of the code.

--- 

### Assumptions before we begin: ###
* Chia is installed on a Linux machine and it is running the farmer (this is important because if it is just a harvester then a lot of the Chia commands won't work).
* You are willing to setup Apache, MySQL, PHP, ssmtp, and code in both Bash and PHP.
* To keep it as simple as possible, Apache, MySQL, and PHP will be setup on the one farmer server. You can set them up on different machines, this was my original method.
* You are familiar with Terminal and some form of editor. Other than viewing the dashboard in a web browser, I pretty much do all the work in the Terminal. I use the editor **nano** but you can use anything you like, just replace **nano** with whatever tool you're using.

...

---

## See the the index.html for more!
