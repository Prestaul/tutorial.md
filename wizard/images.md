# Images

Image syntax is very much like link syntax.

Inline (titles are optional):
`![alt text](/path/to/img.jpg "Title")`

Reference-style:
```
![alt text][id]

[id]: /path/to/img.jpg "Title"
```

Both of the above examples produce the same output:

`<img src="/path/to/img.jpg" alt="alt text" title="Title"/>`