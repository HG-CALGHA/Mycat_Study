### 代理设置

- 设置代理 

  ```
  git config --global http.proxy 代理地址
  ```

- 如果使用后出现 git Received HTTP code 400 from proxy after CONNEC等等错误时

  ```
   rm ~/.gitconfig 
  ```

### git commit 报错

- 当出现unable to auto-detect email address时修改.git文件夹中的config

  ```
  [user]
  email=your email
  name=your name
  ```

  

  

