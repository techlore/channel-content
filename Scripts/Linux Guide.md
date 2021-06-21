# Hello, What Is This?
Believe it or not, we spend days planning out each video (right?), and our device-specific guides receive some of the most attention. Because Linux is more complex than other operating systems, we wanted to have the community check our broad draft before beginning the script. There are many areas for debate and we are hoping to give advice applicable to any user using any distro. Zone 1 is basic, Zone 2 is intermediate, and Zone 3 is advanced. 

We want to hear your feedback so we can make this as good as possible for the world. Feel free to open a PR, or just send us a message on our [web form](https://techlore.tech/contact.html) if you don't use GitHub. This is just a simple checklist and the video itself will go deep into each topic, no need to leave feedback regarding the context of each bullet. 

*All feedback are suggestions and we can choose what to include (Need to say this for some people who don't get that)*

## Distros
Ultimately the user choice, almost every distro (even Ubuntu) is leagues ahead of windows/privacy out of the box for your privacy. Our recommendations for the majority:
- Fedora (overall simple, easy to use, and overall decent security)
- Debian
- Arch (A bit more complex to set up, but has fun things like the AUR) 

## Zone 1
- Strong login & sudo password. Also avoid root login, use sudo.
- Proper Password management for accounts and services 
- Device & File Encryption (LUKS, Veracrypt, etc.)
- Firewall (iptables, firewalld, ufw/gufw, Portmaster)
- Browsers Part 1 (Not Chrome)
- Search Engine (DDG, Startpage, Searx.me)
- VPNs (Proton, IVPN, Mullvad, Windscribe)
- DNS (Same as VPN, or one of the PTIO options)
- Minimalism
- Settings/Permissions
- Updates (Automatic or frequent)

## Zone 2
- FOSS (Using FOSS as often as possible)
- Communication (Secure messengers, email insecurities and improvements)
- Google (Like...delete it)
- Password management part 2 (Use a password manager)
- 2FA (Use it)
- 2FA for user authentication (FIDO hardware tokens, e.g. [YubiKey](https://wiki.archlinux.org/title/YubiKey#Linux_user_authentication_with_PAM), works with sudo as well)
- Browsers Part 2 (Firefox, Tor, Brave, Ung chromium)
- Radios (Disable them when not in use)
- User Accounts (Multiple users for different tasks, most notably a non-admin user for casual use)
- Physical (BIOS lockdown, cover cams, don’t leave device out of site, shut down when leaving for extended periods, device lock)

## Zone 3
- Sandboxing:
  - Firejail
  - AppArmor
  - Even flatpak has some valid pros (and cons)
- Hardening:
  - Basic: https://linuxhint.com/linux_security_hardening_checklist/
  - Intermediate: https://docs.fedoraproject.org/en-US/Fedora/17/html/Security_Guide/chap-Security_Guide-Basic_Hardening.html
  - Advanced: https://github.com/shaurya-007/NSA-Linux-Hardening-docs
- SELinux, and not [turning it off before attempting to learn](https://www.youtube.com/watch?v=_WOKRaM-HI4)
- VMs, Dual-booting, "Advanced Distros", and live operating systems
- Snip-Snip (remove all cams & mics)
