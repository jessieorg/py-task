# 使用方式

```python
def tst1():
    return 0, "开始执行"


def tst2():
    time.sleep(5)
    return 0, "执行..."

def tst3():
    return 0, "执行完毕"



def main():
    _ = run_task("tst1", tst1)
    _ = run_task("tst2", tst2)
    _ = run_task("tst3", tst3)
```