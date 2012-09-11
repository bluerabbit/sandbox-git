* git rebase -i HEAD~(最新のコミットから消したいコミットまでのコミット数)
* エディタ上で、削除したいコミットの行を丸ごと削除する
* エディタ終了
* git rebase --continue
* git push -f