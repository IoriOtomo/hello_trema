課題
tremaが開始した時に
"Hi! from HelloTrema"
と表示するように改造した。
その際、"HelloTrema"の部分はクラス名を参照するようにした。
具体的には、以下のようにコードを変更した。

def start(_args)
    logger.info "Hi! from #{self.class}"
  end
