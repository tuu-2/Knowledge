# Knowledge



## Selenium

### アンカーテキストを指定してクリックをする

```
driver.find_element_by_link_text(u"テキスト").click()
```

### 現在のページURLを取得する

```
value = driver.current_url
```

### 現在のページソースを取得する

```
value = driver.page_source
```