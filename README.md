# [:computer::arrow_right: Latest releases here :arrow_left::computer:](https://github.com/chhjel/Releases/releases/tag/999999)

------

<details><summary>GitUtil Help</summary>
<p>

## GitUtil
* Run once to setup config with required values, then optionally open `GitUtil.config` and set any optional values.
* The first worktree creation per repo can take a minute or two for large repos.
* Does not currently work for remotes using SSH keys with passphrases.

#### Visual Studio shortcuts
Do not choose `Use output window` since input is required.

##### Simple QuickFix
`quickfix --repo $(SolutionDir) --file $(ItemPath) --line $(CurLine) --column $(CurCol)`
##### QuickFix with a clean worktree every time
`quickfix --repo $(SolutionDir) --file $(ItemPath) --line $(CurLine) --column $(CurCol) --clean`
##### QuickFix with custom commands
`quickfix --repo $(SolutionDir) --file $(ItemPath) --line $(CurLine) --column $(CurCol) --command1 "C:\Program Files\Git\git-bash.exe" --args1 {dash}{dash}cd="{RepoFolder}"`

</p>
</details>
