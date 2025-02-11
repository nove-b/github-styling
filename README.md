# Github styling 

This is a fork from [github-style](https://github.com/MeiK2333/github-style) with some additional features that I made.
This is a fork from [github-style-plus](https://github.com/kurt-liao/github-style-plus) with some additional features that I made.

> In this repo, the documentation only introduce additional features.
> For more information about basic usage, please follow the original repo.

## Quick guide

### New features in this fork version:

- [X] 投稿ページのタグ一覧を削除
- [X] 抜粋を最大140字にする
- [X] Mastodonのアイコンを追加
- [ ] Google アナリティクスの確認をする
- [ ] 固定ページを追加できるようにする

## Demo

First, take a look at my [blog](https://blog.nove-b.dev/), it's the completely demo for this theme.

## Usage

### Init hugo site

```bash
hugo new site mysite
cd mysite
```

### Install the theme

```bash
git submodule add https://github.com/nove-b/github-styling.git themes/github-styling
```

### Update the theme

If you just installed the theme, it is already in the latest version. If not, you can update using the below commands

```bash
cd themes/github-styling
git pull
```

Then, you need to rename the previous `posts` folder to `post`

```bash
cd <you-project-folder>
mv content/posts content/post
```
