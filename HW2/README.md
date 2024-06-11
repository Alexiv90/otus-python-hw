# new_opcode.patch
Добавляет новый опкод `LOAD_OTUS`, совмещающий `LOAD_CONST` и `LOAD_FAST`
# until.patch
Добавляет новую конструкцию (`until`) https://eli.thegreenplace.net/2010/06/30/python-internals-adding-a-new-statement-to-python/
# inc_dec.patch
Добавляет новые операторы инкремента и декремента (`++`/`‑‑`) https://hackernoon.com/modifying-the-python-language-in-7-minutes-b94b0a99ce14

## Пример применения
```
git clone https://github.com/python/cpython.git
cd cpython
git checkout 2.7
git apply *.patch
./configure
make
./python
```
