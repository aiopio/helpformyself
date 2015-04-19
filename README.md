#帮助我自己helpformyself

# for my use linux system

# this site first have db

# Todo

## db desgin

```
-- article
 id
 type
 title
 subtitle
 keyword
 content
 status
 creator_id
 created_at
 edited_at
-- read_article
 id
 article_id
 creator_id
 created_at
-- like_article
 id
 article_id
 status
 creator_id
 created_at
-- comment
 id
 article_id
 reply_comment_id
 content
 creator_id
 created_at
```


