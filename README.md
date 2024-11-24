# What I did

## DB

1. "score":16882

```sql
ALTER TABLE `comments` ADD INDEX `post_id_idx` (`post_id`);
```

2. "score":18128

```sql
CREATE INDEX `index_comments_on_user_id` ON `comments` (`user_id`);
```

# app.rb

TBW
