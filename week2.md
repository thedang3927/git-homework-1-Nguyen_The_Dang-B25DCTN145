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
