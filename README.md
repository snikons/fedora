# fedora

```text
# Find fedora version
cat /etc/fedora-release

# Enable the free RPM Fusion repository
# ref: https://docs.fedoraproject.org/en-US/quick-docs/rpmfusion-setup/
sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm
sudo dnf install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

# Install Broadcom driver
sudo dnf install kmod-wl
```

