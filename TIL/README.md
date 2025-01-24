### Today I Learn..

### To remember..
1. git push error
- Internet connection error
- When posting commits to git server, buffer is not enough to upload.
- Solution:
    ```
    $ git config http.postBuffer 524288000
    ```
