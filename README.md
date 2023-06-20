# hexo-asset-image

修改版

```
- var endPos = link.lastIndexOf('.');
+ var endPos = link.length-1;
```

Give asset image in hexo a absolutely path automatically

# Usege

```shell
npm install https://github.com/Horus-K/hexo-asset-image --save
```

# Example

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](logo.jpg)` to insert `logo.jpg`.

# History

2018-04-18: support hexo-abbrlink
