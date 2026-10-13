# Clone dự án từ Git

`git clone <URL> [thu-muc]` tải các tệp và lịch sử của repository về máy, tạo remote origin trỏ tới nguồn.

Nguồn: https://github.com/codegym-vn/wf-hello

Kết quả thực tế:

```text
Clone: git clone https://github.com/codegym-vn/wf-hello.git

$ git remote -v
origin	https://github.com/codegym-vn/wf-hello.git (fetch)
origin	https://github.com/codegym-vn/wf-hello.git (push)

$ git log -1 --oneline
ce2374c Update README.md

$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Các tệp: hello.txt
README.md
```
