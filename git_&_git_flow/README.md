# Git & Git Flow

## Git

### Commit

`DEV-12 #time 25m #comment Cancel sending email at staging env.`

* İngilizce olmalıdır.
* Issue numarası mutlaka olmalıdır.
* Harcanan süre mutlaka olmalıdır.
* Comment cümle şeklinde olmalıdır. Büyük harf ile başlamalı ve ne yapıldığı yazılmalıdır.

### Gitignore

* OS, IDE veya Text Editör dosyalarını global gitignore ekle.
* Framework dosyaları için `.gitignore` dosyası kullan.

### Araçlar

* [oh-my-zsh - git plugin](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/git)
* [oh-my-zsh - gitignore plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/gitignore/gitignore.plugin.zsh)

## Git Flow

![Git Flow](http://danielkummer.github.io/git-flow-cheatsheet/img/git-flow-commands.png)

* Repo yönetimi için fork/push kullanmıyoruz.
* `git flow init` komutu master branchta çalıştırılmalıdır.
* Geliştiriciler her yaptıkları ayrı `feature/branch` ta yapmalı ve branchları `publish` etmelidir.
* Diğer geliştiriciler publish edilen feature/branchı review etmeli ve finish edip develop brancha otomatik merge etmelidir.
* Branch isimleri `onur_ozgur_ozkan` gibi yılan şeklinde olmalıdır. Hepsi küçük harf ve kelimeler arasında `_` alt çizgi olmalıdır.


### Araçlar

* [oh-my-zsh - git-flow plugin](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/git-flow)

## Kaynaklar

* http://nvie.com/posts/a-successful-git-branching-model/
* http://danielkummer.github.io/git-flow-cheatsheet/index.tr_TR.html
* https://confluence.atlassian.com/display/FISHEYE/Using+smart+commits
