# My ansible configs

This repo contains Ansible infrastructure to quickly and reliably set up my private machines.
It has been inspired by [Jeff Geerling](https://www.jeffgeerling.com/)'s [mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook/tree/master).

## Roadmap

Here are my desiderata:
- For now, I'm using Fedora + Gnome, but I might want to switch to Ubuntu or Arch as base and to some tiling Window manager
- I have machines with different purposes:
  + General purpose laptops
  + A proper desktop with nice GPU for streaming, video-related tasks plus GPU-programming
  + A server with GPU for compute purposes
  + A server without GPU for maintenance purposes

  I don't know yet, whether I want/should manage all these devices from this repo or whether I need multiple repos (feedback welcome!)
- Depending on the purpose, there are different applications that should be installed
- However, I need an easy way to replicate secrets across devices

This all seems like a lot to ask and I'm still learning Ansible. Hence, I need to start slow and take it step-by-step.

1. Create a playbook that can replicate my laptop on another laptop
1. Re-install my laptop at least thrice per week to check whether reproducibility works
1. Re-install my main private laptop
1. Re-install my maintenance server and check whether different environments can be easily supported
1. Re-install the GPU server
1. Re-install the GPU desktop

## Author

[Michael Tiemann](mailto:github@michaeltiemann.net)
