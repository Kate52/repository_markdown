## Заголовок 2 уровня

Ненумерованный список

- List
- List
- List

Нумерованный список

1. List
2. List
3. List

`Inline code`

```
<h1>Sample heading</h1>
```

*Italic text 1*

**Bold text 1**

 > Blockquote text.

[Link](https://example.com/)

```javascript
function doSomething() {
	// Write code here
}
```

- [ ] incomplete task
- [x] completed task

# Examples

Set `plantuml:{filename}` as a fence information. `filename` is used as the file name of generated diagrams. In the following case, `md-sample-sequence.svg` is created.
`filename` is required.

```plantuml:md-sample-sequence
@startuml
actor Foo123
boundary Foo2
control Foo3
entity Foo4
database Foo5
collections Foo6
Foo1 -> Foo2 : To boundary
Foo1 -> Foo3 : To control
Foo1 -> Foo4 : To entity
Foo1 -> Foo5 : To database
Foo1 -> Foo6 : To collections
@enduml
```

![](./md-sample-sequence.svg)
