# mig-paste
Copy image to container

## Idea

用 powershell 的命令，
$img = Get-Clipboard -format image
$img.save("c:\abc.png")

来做粘贴

然后通过docker 命令拷贝进容器，并且更新 markdown 。
