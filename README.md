# neofetch
Neofetch Custom with Docker Logo Added

### Installation
1. Copy neofetch to <code>/usr/bin</code>
2. In <code>/usr/bin</code> run <code>chmod 715 neofetch</code>
3. Download config.conf and copy to <code>/etc/neofetch/config.conf</code>

### Execution
Write in <code>~/.bashrc</code> the following code:
<br>
<code>
neofetch --config /etc/neofetch/config.conf --ascii_distro _Distro_
</code>
<br>
_Distro_ (Ubuntu, Docker, SteamOS, etc)

More info in: https://github.com/dylanaraps/neofetch/blob/master/neofetch
