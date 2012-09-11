①git rebase -i HEAD~(最新のコミットから消したいコミットまでのコミット数)
②エディタ上で、削除したいコミットの行を丸ごと削除する
③エディタ終了
④git rebase --continue
⑤git push -f