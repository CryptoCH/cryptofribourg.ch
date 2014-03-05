#cryptofribourg.ch

Pages du wiki http://cryptofribourg.ch.

Le wiki utilise [DokuWiki](https://www.dokuwiki.org/dokuwiki) avec le plugin
[gitbacked](https://www.dokuwiki.org/plugin:gitbacked).

##gitbacked

Le plugin est configurécomme suit:

```php
$conf['plugin']['gitbacked']['pushAfterCommit'] = 1;
$conf['plugin']['gitbacked']['periodicPull'] = 1;
$conf['plugin']['gitbacked']['periodicMinutes'] = 10;
$conf['plugin']['gitbacked']['repoPath'] = './data/git_pages';
$conf['plugin']['gitbacked']['repoWorkDir'] = './data/git_pages';
$conf['plugin']['gitbacked']['addParams'] = '-c user.email=anon@cryptoch.org -c use
r.name=CryptAnon';
$conf['datadir'] = './data/git_pages/pages';
$conf['mediadir'] = './data/git_pages/media';
```
