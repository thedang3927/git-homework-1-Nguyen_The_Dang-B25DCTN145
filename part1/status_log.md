##ptithuuduyen##

##Create three files: notes.txt, todo.txt, draft.md. Run git status and paste the output to a file status_log.md##

On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	../.gitignore
	./

nothing added to commit but untracked files present (use "git add" to track)




##Stage only notes.txt and todo.txt (leave draft.md unstaged). Run git status again and record in status_log.md.##

On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   notes.txt
	new file:   todo.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	../.gitignore
	draft.md
	status_log.md




##Modify notes.txt (add at least 3 lines of text). Use git diff to view the unstaged change, then git diff --staged after staging — copy outputs into status_log.md.##

diff --git a/part1/notes.txt b/part1/notes.txt
index 519dd58..1e20df6 100644
--- a/part1/notes.txt
+++ b/part1/notes.txt
@@ -1 +1,6 @@
 note
+1
+2
+3
+4
+5




##Commit using git commit -a -m "Update notes.txt" — explain in status_log.md why this works only for already-tracked files.##

Bởi vì " -a" trong câu lệnh git commit -a -m "Update notes.txt" là tự động staging modified tất cả các file đã tracked,
còn những file untracked như những file draft.md và status_log.md thì sẽ không được thêm vào staging area nên sẽ không được commit.




##Document the difference between fetch and pull in status_log.md##

fetch là lấy commit mới từ remote về local repo nhưng không thay đổi file hiện tại, 
còn pull lấy commit mới từ remote về local repo và sau đó merge lịch sử của remote và local 


