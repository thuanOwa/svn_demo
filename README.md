svn checkout --depth empty https://github.com/thuanpham2311/svn_demo



## Windows 10

- sử dụng visualsvn để tạo svn server

## một số lệch tương tác svn


```pwsh
$env:editor = '{editor name, vd: notepad, nvim}'
```
> tạo biến môi trường echo editor để svn sử dụng xử lý conflict

```bash
svn checkout {server url}
svn update {update lastest}
svn update -r{number}
svn merge {feat} {trunk}
```
