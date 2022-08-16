# [:computer::arrow_right: Latest releases here :arrow_left::computer:](https://github.com/chhjel/Releases/releases/tag/999999)

------

<details><summary>GitUtil Help</summary>
<p>

## GitUtil
* Run once to setup config with required values, then optionally open `GitUtil.config` and set any optional values.
* The first worktree creation per repo can take a minute or two for large repos.
* Does not currently work for remotes using SSH keys with passphrases.

#### Visual Studio shortcuts
Do not choose `Use output window` since input is required. For faster operations use the quickfix2 command instead of quickfix. It invokes git cli directly instead of using lib2git. 

##### Simple QuickFix
`quickfix2 -r $(ItemPath) -f $(ItemPath) -l $(CurLine) -c $(CurCol)`

##### QuickFix with a clean worktree every time
`quickfix2 -r $(ItemPath) -f $(ItemPath) -l $(CurLine) -c $(CurCol) --clean`

##### Quickfix + ask for issue id that will be used in PR title and branch name
`quickfix2 -r $(ItemPath) -f $(ItemPath) -l $(CurLine) -c $(CurCol) --ask-for-issue-id`

##### QuickFix with custom commands
`quickfix2 --repo $(SolutionDir) --file $(ItemPath) --line $(CurLine) --column $(CurCol) --command1 "C:\Program Files\Git\git-bash.exe" --args1 {dash}{dash}cd="{RepoFolder}"`


</p>
</details>
