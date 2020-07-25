# Norihito Ishida's personal website
 
## Abstract
- Host : [Github Pages](https://pages.github.com/)
- Static site generator : [Hugo](https://gohugo.io/)
- Hugo Themes : [Coder](https://themes.gohugo.io/hugo-coder/)

## How to update website
- Change directory : `cd hogehoge/blog/personal-website`
- Add Some Content : `hugo new posts/mypost.md`  ([example](https://gohugo.io/getting-started/quick-start/#step-4-add-some-content))
- Check on localhost : `hugo serve` (Web Server is available at http://localhost:1313/)
- Build website : `hugo` (Built contents are published on personal-website/docs)
- Git push : `git add * && git commit -m "msg" && git push`
- Change directory : `cd hogehoge/norihitoishida.github.io` (personal-website/docs is remote repository of this)
- Git push : `git add * && git commit -m "msg" && git push`
- Update complete! (Website is available at https://norihitoishida.github.io/ )

## Useful resources
- [Github pages + Hugoでブログ構築](https://yonehub.y10e.com/2019/10/22/20191022_hugo_githubio/)
- [Hugoを導入してWebサイトをGitHub Pagesで公開してみた話](https://qiita.com/akivajp/items/1fd52a610e3eed5b7758)

## Tips
- ".nojekyll" file is necessary because Github would fail to build website.