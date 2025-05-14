## Nolva's Homepage

4. **计算最终价格**：
   ```python
   final_price = price * (1 - discount_rate)
   ```
   - **公式解析**：
     - `discount_rate`为折扣率，乘以价格`price`后得到折扣部分。
     - `1 - discount_rate`为保留部分，用原价`price`乘以这个保留部分，得到扣除折扣后的最终价格。

6. **优化建议**：
   - **参数合法性检查**：在调用函数前，应确保`price`为正数，`discount_rate`在0到1之间。若检查通过，增加进一步的信息提示用户。

以下是更新后的完善版本：

```python
def calculate_discount(price, discount_rate):
    """
    计算商品在应用折扣率后的最终价格。
    """
    print(123)
```
