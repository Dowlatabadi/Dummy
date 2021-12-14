# dummy repo for the snippets

# powershell 
## polling with for loop
```powershell
#checking for the docker demon to restart and work!!
 For ($i=0; $i -le 10; $i++) {  docker ps; Start-Sleep -s 10}
```
## scp, remote trasfer through ssh
```powershell
 scp -v -r "c:\...\shared-remote\mycashimage.tar.gz" username@192.168.18.244:C:\Users\b.username\Desktop\docker_images
```

