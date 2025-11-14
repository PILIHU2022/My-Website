+++
title = "修Neovim配置有感"
date = "2025-11-14T18:33:53+08:00"
tags = [ "Neovim" ]
+++
# Why？
最近~~偶然~~开机，立即开始了Arch Linux每日一滚😋。不出所料，Neovim也更新了，当我编辑一个文本的时候，提示LSP配置太老了需要更改一下。

## Process
于是我开始了排错，一直排到文件的[第26行](https://github.com/PILIHU2022/My-dotfiles/blob/ef5de51dcb3fb60ff7c3a95b687cbb6a99d98281/.config/nvim/lua/plugins/lsp.lua#L26)。突然发现自己抄的屎山搞得自己不会改了。~~其实也没啥耐心看文档了~~，那时候正愁着准备要去上学了。一直等了2周左右，才开始改起来，也成功地改好了。

# Thought
抄别人的配置当然可取，也很推荐去抄一些社区驱动的，更新及时的dotfile。

但自己维护一份dotfile也不是不行，就是看自己是否愿意付出这份时间以及精力。

当然，自己用着舒服才是最终的目的，也会在成功后有一种自豪感。

但不要~~杂交~~别人的配置。我这份Neovim的配置就是杂交了几个人的，现在修起来很麻烦😅

也推荐去读读[LAST](https://github.com/LAST7/)的[这一篇文章](https://blog.imlast.top/2025/06/22/configuration-engineering/)

### 此致-Spark.
