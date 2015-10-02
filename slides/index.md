- title : language
- description : open your mind by learning to think differently
- author : Martin Schinz
- theme : league
- transition : default

***

### Why Language matters

<ul>
    <li class="fragment fade-in">Exchange of ideas</li>
    <li class="fragment fade-in">Express inner state</li>
    <li class="fragment fade-in">Model the world</li>
    <li class="fragment fade-in">Freedom</li>
</ul>


![Intersection of thoughts](images/the-conversation.jpg)


***

- data-transition : zoom

### What does it mean to be free?

- Physical
- Political
- Emotional
- “Freedom of __Thought__” — George Orwell 1984
 [https://en.wikipedia.org/wiki/Newspeak](https://en.wikipedia.org/wiki/Newspeak)<br />
 [Some Characteristics of the Dual in Slovenian (http://www.slav.uni-sofia.bg/naum/en/node/1639)](http://www.slav.uni-sofia.bg/naum/en/node/1639)

' Prison
' Communism
' Love sick (needs better)
' (NewSpeak / George Orwell)
' Slovenian


***

### Why should I care ?

#### <span class="fragment zoom-in">I use Programming _Languages_</span>

- Today code is written for people, not machines
- Different languages enable different ways of thinking
- Expressiveness enables higher levels of abstraction
- Context matters (jvm / node / erts / native)

***

### Language Taxonomy

**Paradigms**

- OO
- FP
- Relational

---

### Programming Language history


[Relationship Diagram](http://exploringdata.github.io/vis/programming-languages-influence-network/)

[© Ramiro Gómez](http://ramiro.org/) ([@yaph](https://twitter.com/yaph))

---

#### F#

    let a = 5
    let factorial x = [1..x] |> List.reduce (*)
    let c = factorial a

---

#### C#

    [lang=cs]
    using System;

    class Program
    {
        static void Main()
        {
            Console.WriteLine("Hello, world!");
        }
    }

---

#### JavaScript

    [lang=js]
    function copyWithEvaluation(iElem, elem) {
        return function (obj) {
            var newObj = {};
            for (var p in obj) {
                var v = obj[p];
                if (typeof v === "function") {
                    v = v(iElem, elem);
                }
                newObj[p] = v;
            }
            if (!newObj.exactTiming) {
                newObj.delay += exports._libraryDelay;
            }
            return newObj;
        };
    }


***

### The Reality of a Developer's Life 

**When I show my boss that I've fixed a bug:**
  
![When I show my boss that I've fixed a bug](http://www.topito.com/wp-content/uploads/2013/01/code-07.gif)
  
**When your regular expression returns what you expect:**
  
![When your regular expression returns what you expect](http://www.topito.com/wp-content/uploads/2013/01/code-03.gif)
  
*from [The Reality of a Developer's Life - in GIFs, Of Course](http://server.dzone.com/articles/reality-developers-life-gifs)*

