# paper
以后要读的论文？

## 项目内容

- `paper_mthd.md`：三遍阅读法笔记。
- `语义分割/`：语义分割相关论文 PDF。
- `.vscode/settings.json`：本项目的 Git 与 GitHub 设置。

## 在 VS Code 中上传后续修改

1. 在 VS Code 打开 `D:\论文`，按 `Ctrl+Shift+G` 打开“源代码管理”。
2. 检查变更，点击文件旁边的 `+` 暂存需要上传的文件。
3. 输入提交说明，选择“提交并推送”。也可以先“提交”，再点击“同步更改”。
4. 上传目标为 `codeMarshuo/paper` 的 `main` 分支。

等价的终端命令（在项目目录运行）：

```powershell
git add --all
git commit -m "描述本次更新"
git push
```

项目使用 HTTPS 和本机 Git Credential Manager 保存的 GitHub 登录。不要把访问令牌、密码或私钥写入项目文件。新设备首次推送可能需要登录 GitHub。
