# donejs-unikernel
A Generator that Adds Unikernel Build Support to DoneJS Applications

## Supported Unikernels
- Capsan (OSv)
- Custom via https://github.com/stealify/image-builder-rpi
  - To build a Custom Unikernel you need 2 Parts the Boot Initrd and a FileSystem Optional 
- Stealify OS (Default) supports Docker Containers
- NodeOS support is in Work it trys to get stable.
- Rampkernel Support is in progress


## What are the Concepts behind Unikernels?
It Creates a Bundle with a Minimal OS to get your Application up and Running so that you can deploy it to bare metal or the cloud without additional steps and configuration managment so you can focus on your application and forget about the underlaying userland of the Operating System as your Application is the Userland.

if your not familar with all the parts of a Operating System and your a Docker or Moby User this is exactly what you want.
you abstract the Administration effort for extra Operating Systems away and all the security stuff. I will talk about that in one of my Videos later.

## Features
- A Complet VM That Boots in Under a Secund in Best case
- Abstract away Most of the OS Layer reduce it to Drivers.
- Be Your Own Init Process aka PID 1
- Better Security
- Faster Deployment
- More Stable in Development to Production 
- External Tests of The Complet Applications as in Production even in Development
- No Additional Tests per Component needed as long as the Component acts as expected in Application.
- Most Amazing Development Cycle Ever.



mfg Frank Lemanschik Author of DoneJS Unikernel Support by the way the here used Packaging method will work with any Application based on Linux or windows with slight adjustments if you need help to build Unikernel Support for your Deployments or if your A company that seeks into the next Level of Deploying Software while Development and in Production simply reach out.
