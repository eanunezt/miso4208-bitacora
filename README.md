# gitboook-publishable-template
template to use for publishing gitbooks to github.com

You can duplicate this repository 
https://help.github.com/articles/duplicating-a-repository/

1. Create a new repository on github.com  


2. Create a bare clone of this repository
`git clone --bare https://github.com/rebeccapeltz/gitbook-publishable-template.git`

3. Mirror-push to new repository
`cd gitbook-publishable-tempalte.git`  
`git push --mirror https://github.com/useraccount/new-repository.git`  

4. Remove the temporary repository create above  
`cd ..`
`rm -rf old-repository.git`  


