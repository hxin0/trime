## 小鹤双拼安装说明
### 将以下小鹤双拼方案文件和配置拷贝入以下文件夹：
#### Nexus 5: <root>`\Internal storage\rime`
#### Samsung: <root>`\rime`
- default.yaml
- flypy.schema.yaml

### 其他说明
- 小鹤双拼输入方案，来自

    https://github.com/hxin0/rime-double-pinyin.git  
    `rime-double-pinyin/double_pinyin_flypy.schema.yaml`    
- 更改schema name为: flypy
- 翻页选择每页条目： 10
- 修改文件名`double_pinyin_flypy.schema.yaml`->`flypy.scheme.yaml`
- `default.yaml`:

```
schema_list:
  # - schema: bopomofo_tw
  # - schema: luna_pinyin
  # - schema: terra_pinyin
  - schema: flypy
menu:
  page_size: 10
```

- `flypy.scheme.yaml`:

```
schema:
  schema_id: flypy
```

#### Nexus
最初用ES File Explorer拷贝文件
- menu -> `Local` ->`Internal Storage`
- 显示路径：`/` > `storage` > `emulated` > `0` > `rime`

拷贝后，在Windows下
- 出现`<root>\rime`文件夹
- `rime`文件夹下只有拷贝的两个文件，其他文件不可见
