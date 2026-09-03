PART A
1.
 [main 451f9a7] Add week3.md report file
 3 files changed, 1 insertion(+), 3 deletions(-)
 delete mode 100644 test.txt
 delete mode 100644 text.txt
 create mode 100644 week2.md
 
 M       week2.md
 Switched to branch 'week2'

2.
 [week2 8fd0fba] working 1
 1 file changed, 2 insertions(+)
 create mode 100644 working.txt

 [week2 1ef81a3] working 2
 1 file changed, 1 insertion(+)

3.nguyenthedang
 [week2 021a62a] Update week2.md on branch week2
 1 file changed, 21 insertions(+)

finding: Khi chuyển lại nhánh main, dòng được thêm vào nhánh week2 đã biến mất vì commit đó chỉ tồn tại trên nhánh week2 và chưa được merge vào nhánh main.

4.
 Merge made by the 'ort' strategy.
 week2.md    | 25 +++++++++++++++++++++++++
 working.txt |  3 +++
 2 files changed, 28 insertions(+)
 create mode 100644 working.txt


PART B
1.
 Updating 451f9a7..72803b7
 Fast-forward
 week2.md    | 25 +++++++++++++++++++++++++
 working.txt |  3 +++
 2 files changed, 28 insertions(+)
 create mode 100644 working.txt

2.
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git branch --merged
* main
  week2b
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git branch --no-merged
  wip

3.
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git branch -d week2b
Deleted branch week2b (was 9256bf7).

4.
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git branch -m wip work-in-progress
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git push -u origin work-in-progress 
Enumerating objects: 38, done.
Counting objects: 100% (38/38), done.
Delta compression using up to 12 threads
Compressing objects: 100% (31/31), done.
Writing objects: 100% (37/37), 3.50 KiB | 1.17 MiB/s, done.
Total 37 (delta 17), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (17/17), done.
remote: 
remote: Create a pull request for 'work-in-progress' on GitHub by visiting:
remote:      https://github.com/thedang3927/git-homework-1-Nguyen_The_Dang-B25DCTN145/pull/new/work-in-progress
remote: 
To https://github.com/thedang3927/git-homework-1-Nguyen_The_Dang-B25DCTN145.git
 * [new branch]      work-in-progress -> work-in-progress
branch 'work-in-progress' set up to track 'origin/work-in-progress'.

PART 4
1.
 nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 16 commits.
  (use "git push" to publish your local commits)
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git checkout -b experiment
Switched to a new branch 'experiment'
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ vim exp1.txt
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git add exp1.txt 
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git commit -m "add file exp1.txt"
[experiment 4fb156f] add file exp1.txt
 1 file changed, 1 insertion(+)
 create mode 100644 exp1.txt
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ vim exp2.txt
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git add exp2.text
fatal: pathspec 'exp2.text' did not match any files
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git add exp2.txt
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git commit -m "add file exp2.txt"
[experiment 91b09f1] add file exp2.txt
 1 file changed, 2 insertions(+)

2.
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 16 commits.
  (use "git push" to publish your local commits)
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ vim newfile.txt
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git add newfile.txt 
nguyen-the-dang@nguyen-the-dang:~/git-homework-1-Nguyen_The_Dang-B25DCTN145$ git commit -m "add newfile.txt"
[main 0d0cd86] add newfile.txt
 1 file changed, 2 insertions(+)
 create mode 100644 newfile.txt

