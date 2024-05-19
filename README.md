---
title: "About"
permalink: "/about/"
layout: page
---
  
Hello my name is Josh, and here I'll be posting update on the various projects and homelab technologies I'm working with.  
This site is hosted using [GitHub Pages][github-pages] with a fork of a [Jekyll][jekyll] theme as the main HTML coding.  

Currently *5/18/24* Server Setup is a:  
* Proxmox machine using a Ryzen 5 2600x, Nvidia GEFORCE GTX 960, 16GB DDR4 RAM, 512GB SATA SSD, 1TB SATA HDD
  - Current Services:
    - [PiHole DNS][pihole]
    - DuckDNS
    - Portainer
    - [GNS3][gns3]
    - [Wireguard][wireguard]
    - [Dashy][dashy]
* Main computer/[LLama3][llama3] host with a Ryzen 5 5600x, Radeon RX 6600XT, 32GB DDR4 RAM, 1TB NVME SSD  

Current Networking Hardware:  
* TP-Link tl-sg105e 1GB 5 port managed switch
* TP-Link POE injector
* TP-Link EAP223
* APC UPS BE550G
* Navepoint 12U rack  

# Future Plans
- [ ] Organize my current homelab setup better
- [x] ~~Set up a dashboard ([Dashy?](https://dashy.to/)) for quick access all my services~~ (5/12/24)  
- [ ] Learn more about [Ansible](https://www.ansible.com/) and [Terraform](https://www.terraform.io/) and see if deploying them would be useful  
  - [ ] Learn YAML  
- [ ] [Ollama](https://ollama.com/library/llama3) seems interesting, but I'm unsure if I could reasonably run it 24/7 with my current resources  
- [ ] Get a larger (> 8 port) POE+ switch
  - [ ] Potentially move away from decentralized security and utilize a self-hosted NVR
- [ ] Create a NAS machine(s)
- [ ] Locally create SSL certificates for my services

[github-pages]: https://pages.github.com/
[jekyll]:       http://jekyllthemes.org/
[pihole]:       https://pi-hole.net/
[gns3]:         https://www.gns3.com/
[wireguard]:    https://www.wireguard.com/
[dashy]:        https://dashy.to/
[llama3]:       https://ollama.com/


