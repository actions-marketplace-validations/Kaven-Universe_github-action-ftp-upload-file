# github-action-ftp-upload-file

This action uploads the file to the ftp(s) server.

## Example usage

```yml
- name: Upload
  id: upload
  uses: Kaven-Universe/github-action-ftp-upload-file@v0.0.1
  with:
    server: ftp.server.com
    port: 21
    username: xxx
    password: ******
    file: "name.txt"
    rename-file-to: "newName.txt"
    json_stringify_data: '["file1","file2","..."]'
```
