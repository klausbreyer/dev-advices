---
title: "Operations"
bg: purple
color: white
fa-icon: gears
---

### Always be up to date

Try to use the latest (and **stable**) version. This is true for everything out there: your coding language, your database management system, your libraries, your assets.

The not so obvious reason behind this guideline: The bigger your app is getting in the future, the more difficult it might get to upgrade it. Every single feature you add to your code base needs testing. If you haven't any automated testing, the only in-depth testing will happen directly within the implementation itself. so it's better to start with the newest available version, although you might not have any experience with it.

But, distro X is not supporting component Y in version Z. Try to find a stable PPA (like the famous [ondrej-ppas](https://launchpad.net/~ondrej) for php5)

### Automate all the things

The more "ready to use" shell commands you have, the better! If you find a reocurring job, try to script it.

##### Advantages

- Time saver
- You don't need to reinvent the wheel each time
- Kind of "secure feeling" for new employees/standby team members

#### Examples

- Deployment Script
- Database Sync script
- App-specific jobs

#### Think API first

Forget about mobile first (this might be a topic for another guide). Think API first. Decoupling frontend and backend is always a good idea.

##### Rule of thumb

Frontend should be as stupid as possible. All the logic / data processing / validation should be in the backend / API. Then you don't need to reinvent the wheel for every client app again and again.
