# kesh { }

<p>&nbsp;</p>
<p align="center" width="100%"><img width="33%" alt="heyiya-if symbol" src="https://upload.wikimedia.org/wikipedia/commons/c/c2/Double_spirale.svg"></p>
<p>&nbsp;</p>

> A long, long time from now, in the wake of what will no longer be called JavaScript, might be going to have existed a programming language called _kesh_.


```lua
#kesh 2021

#person: [
    name: #string
    age: #number
]

greet(person: #person) #string: {
    name: person.name
    "Hey, { name }!"
}

joe: [
    name: 'Joe'
    age: 27
]

print greet(person: joe)  --> 'Hey, Joe!'
```

The syntax is a strict superset of [na](https://github.com/kesh-lang/na).

---

<sup>[heyiya-if symbol](https://commons.wikimedia.org/wiki/File:Double_spirale.svg) is [CC0](https://creativecommons.org/publicdomain/zero/1.0/)</sup>
