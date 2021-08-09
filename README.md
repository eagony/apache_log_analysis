# apache_log_analysis
Apache日志分析


```python
url_report = {
    '/coding/miniprj/material.html':
        {
            'title': '训练素材',
            'visits_count': 20,
            'ip_count': 4
        }
}

ip_report = {
    '200.200.76.130': {
        'visits_count': 40,
        'page_visited_count': 15
    }
}

full_report = {
    '/coding/miniprj/material.html':{
        '200.200.76.130': 3
    },
    '/coding/style/%E7%BC%96%E7%A0%81%E9%A3%8E%E6%A0%BC.zip':
    {
        '200.200.76.130': 1
    },
    '/designing/tools/image/UML_classes.docx':
    {
        '177.1.81.42': 1
    }
}
```