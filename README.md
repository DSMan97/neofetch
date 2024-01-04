# neofetch
Neofetch Custom Logos Added:
 - Docker  Logo
 - Kubernetes Logo
 - SteamDeck Logo
 - Jenkins Logo

### Installation
1. Copy neofetch to <code>/usr/bin</code>
2. In <code>/usr/bin</code> run <code>chmod 715 neofetch</code>
3. Download config.conf and copy to <code>/etc/neofetch/config.conf</code> or <code>$HOME/.config/neofetch/config.conf</code>

### Optional config file
If you are a cloud developer you can download the config.conf file that are in [config_cloud_developers](https://github.com/DSMan97/neofetch/tree/main/config_cloud_developers)<br>
That file print the versions of the following tools:
- Google Cloud SDK (gcloud and gsutil)
- Azure Cli
- Terraform
- Docker
<br>

**Important!:** Review the config file and modify, comment and changes the paths with your installations path of that tools

- Check the lines from 61 to 83
#### Example of code
```
    echo ""
    echo "                              Cloud Tools"
    info "GCP Login" gcloud_account
    info "GCP ProjectId" gcloud_project
    info "gcloud version" gcloud_version
    info "gsutil version" gsutil_version
    echo ""
    info "Docker" docker_version
    info "Terraform" terraform_version
    info "Azure Cli" azurecli_version
```
![img.png](https://github.com/DSMan97/neofetch/blob/main/config_cloud_developers/img.png?raw=true)

### Execution
Write in <code>~/.bashrc</code> the following code:
<br>
<code>
neofetch --config /etc/neofetch/config.conf --ascii_distro _Distro_
</code>
<br>
_Distro_ (Ubuntu, Docker, SteamOS, SteamDeck, etc)

More info in: 
<br>
<br>
Original File:
<br>
https://github.com/dylanaraps/neofetch/blob/master/neofetch
<br>
<br>
Documentation:
<br>
http://manpages.ubuntu.com/manpages/bionic/en/man1/neofetch.1.html
<br>
<br>
Ascii Color Codes:
<br>
https://www.lihaoyi.com/post/BuildyourownCommandLinewithANSIescapecodes.html#256-colors
<br>
<br>
Neofetch with custom Image:
<br>
https://www.linuxfordevices.com/tutorials/linux/neofetch-in-linux
<br>
<br>
Conver IMG to ASCII ART:
<br>
https://manytools.org/hacker-tools/convert-images-to-ascii-art/go/
