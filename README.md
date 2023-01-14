# golang-shell-scripts
Useful shell scripts I made for golang development

# Scripts 

##  gcm

`gcm "epic commit message"` == `git commit -am "epic commit message"`

## gdf
`gdf` == `git diff`

## gst 

`gst` == `git status` 

## lint 

`lint` == `golangci-lint run` 

## safe-push 

`safe-push` is a more complex script which will ensure tests pass, then run a linter, then show the status of the repo and see if you want to push up your changes. 

The benefits of this are that the actions will not fail.

## tst 

`tst` == `go test ./... --cover` 

