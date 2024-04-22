В ячейке ниже представлен код генерирующий _DataFrame_, которая состоит всего из 1 столбца. Ваша задача перевести его в _one hot_ вид. Сможете ли вы это сделать без _get_dummies_?

```
import random
lst = ['robot'] * 10
lst += ['human'] * 10
random.shuffle(lst)
data = pd.DataFrame({'whoAmI':lst})
data.head()
```
