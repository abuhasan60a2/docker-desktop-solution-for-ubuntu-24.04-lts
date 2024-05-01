# docker-desktop-solution-for-ubuntu-24.04-lts <br/>
The temporary workaround is <br/> 
$ sudo sysctl -w kernel.apparmor_restrict_unprivileged_userns=0 <br/> 
$ systemctl --user restart docker-desktop <br/> 
source: <br/> 
https://www.reddit.com/r/docker/comments/1c9rzxz/comment/l1u2h3x/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button 
