# is-odd-llm

既然 LLM 是如此強大 💪，為何我們不用它檢查一個數字是否為奇數呢？🫣

靈感來自 [is-odd-ai](https://github.com/rhettlunn/is-odd-ai)，這個是 Python 的版本。

![demo](https://imgur.com/jmtOIAK.png)
## 安裝

```bash
pip install is-odd-llm
```

## 使用

設定你的 OpenAI API key 在環境變數 `OPENAI_API_KEY`

```bash
export OPENAI_API_KEY="sk-..."
```

然後你可以使用 `is_odd` 函數來檢查一個數字是否為奇數。

### 範例

```python
from is_odd_llm import is_odd

print(is_odd(1))  # 高機率是 True
print(is_odd(2))  # 高機率是 False
```

## 貢獻

歡迎開 issue 或 PR，一起體驗 LLM 的魔法

## License

[MIT](LICENSE)
