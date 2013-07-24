# badwords
badwords包含一个敏感词库，如果一段字符串中含有敏感词，则返回true，否则返回false


## Install

In your gem file:

```ruby
gem "badwords"
```


## Usage

For example:

```ruby
"testwords".badwords
#=>false

"江青是毛泽东的妻子".badwords
#=>true
```


