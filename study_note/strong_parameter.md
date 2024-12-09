# strong_parameter のネストにするかどうか

- ネストする必要が特別なければ、「フラットなパラメータを許可」でパラメーターを受け取る。

## ネストされたパラメータを許可

```ruby
def test_box_master_params
params.require(:hogehoge).permit(:label, :hogehoge_id)
end
```

## フラットなパラメータを許可

```ruby
def test_box_master_params
params.permit(:label, :hogehoge_id)
end
```
