# Personal Gists

### Contents
- [Setup Shadowsocks Server And Client](https://gist.github.com/jinying-che/ea1a207e6590f4b6b8f62760658a2665)
- [Golang Standard Library - sync](https://gist.github.com/jinying-che/36e56db094f955531a404ad6f3ab02af)
- [Tech Doc Writting Tips](https://gist.github.com/jinying-che/c1a23566e814a291a99a8f3edab4abbb)

### New Post Guide
1. create `xxx.md` 
2. if images are required, add them into [gist comment](https://gist.github.com/jinying-che/648e86b262f25c2c82b8017f8f6a3e18), click the image to get the link
3. publish gist: `gh gist create --public xxx.md` ([gh](https://cli.github.com/) is a command-line interface to GitHub)
4. add submodule: `git submodule add git@gist.github.com:<hash>.git path/to/md/` (do note that use ssh instead of https)
5. remove the files just created (as add submodule will clone the gist and create the file)
6. commit new changes: `git add, commit, push`

### Preview Docs
- [grip](https://github.com/joeyespo/grip) `path/to/doc.md`
