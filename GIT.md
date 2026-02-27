# GIT

Code Versioning
Diff

Branching
git checkout -b <nama branch>
git checkout <nama branch / nama hash>

Undo Commit
git revert
git reset --hard <name hash / nama branch>

Merge
git checkout master // Atau target branch
git merge <nama sumber branch>

Merge Conflict

Pull Request

- Via Github Interface

Rebase

git checkout <source branch - branch yang ada kerjaannya>
git rebase <target branch, biasanya master>

-- resolve conflict satu2 bila ada
-- kalau gagal bisa: git rebase --abort untuk mengulangi

lalu
git checkout <target branch, biasanya master>
git merge <source branch - branch yang ada kerjaannya dan sudah di rebase>

atau
click merge di pull request Github punya interface

convention
branch out -> commit often -> rebase and merge often -> abandon old branch
