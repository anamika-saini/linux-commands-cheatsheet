# Users & Permissions

## Add user
sudo useradd devuser

## Set password
sudo passwd devuser

## Switch user
su devuser

## File permissions

### View permissions
ls -l

### Change permissions
chmod 755 file.sh
chmod 644 file.txt

### Change owner
chown user:user file.txt
