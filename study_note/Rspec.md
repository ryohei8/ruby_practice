# Rspec のテストコードの書き方

- なるべく()は使わない
- .to eq (0)ではなく.to eq 0 のように書く

## binding.pry で止めて、json の body を parse して確認する

pry 上で下記を実行

```ruby
JSON.parse(response.body)
```
