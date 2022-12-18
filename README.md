# Solution for task Cat Class

```python
class Cat:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def info(self) -> dict:
        pass
        return {
            "cat": self.name,
            "age": self.age,
        }

    def voice(self) -> str:
        return f"{self.name}: Meow!"

```
