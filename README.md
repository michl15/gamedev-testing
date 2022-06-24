# gamedev-testing
Test repo for trying out unity

Also for learning Git/Github for those who have not used before

## How do I do the thing
Recently Github removed password authentication which leaves you with two choices SSH authentication or Personal Access Tokens. \
You'll first create a ssh authentication for your machine and then clone this repo using ssh

## How to setup ssh
### create key
go to your favorite terminal and enter \
`ssh-keygen -t ed25519 -C "your_github_email@example.com"` \
You can press enter past all the questions, note that the file will be saved in the `~/.ssh/` folder 
### add to ssh-agent
then you're going to want to add the key to ssh-agent\
with `ssh-add ~/.ssh/<TAB>` \
where <TAB> is the name of your key, but simply pressing tab should autocomplete it
### add to github
follow this guide, you're almost done and it's gonna be worth it \
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

Now you should be able to push and pull with no problems


## Ew yucky Personal Access Tokens
Personal Access Tokens are annoying because you have to paste them in as though they were your password, here's a walkthrough if you're intersted
https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-create-a-GitHub-Personal-Access-Token-example
