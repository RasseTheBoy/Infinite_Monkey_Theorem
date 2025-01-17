
# Infinite Monkey Theorem

We all love monkeys 🐒  
And so do mathematicians and theory lovers as well.

With this script, you give your desired word, and wait for the monkeys to write your sentence.


## Made by

- [@RasseTheBoy](https://github.com/RasseTheBoy)
## TL;DR About the theory

The infinite monkey theorem states that a monkey hitting keys at random on a  
typewriter keyboard for an infinite amount of time will almost surely type any  
given text, such as the complete works of William Shakespeare.

(source: [Wikipedia](https://en.wikipedia.org/wiki/Infinite_monkey_theorem))
## Required libraries

(Only standard libraries)

- threading
- datetime
- string
- random
- time
## Tutorial

1. Run the **main.py** file

```
python main.py
```

```
python3 main.py
```

2. Enter the amount of monkeys (only if **monkey_names.txt** is empty)

3. Give the sentence you want the monkeys to generate

4. Wait...


## Demo

![demo video](https://media.giphy.com/media/05G5vtY24iqSV6hTer/giphy.gif)
## monkey_names.txt

You can give each monkey its own unique name.  
Just write them as shown below:  

```
Mike
Alfonso
Herbert
Yoda
```
If this file is empty, the code asks how many monkeys to create.  
(The default name for a monkey is "Mike")

## Output

| Output        | Description |
| ------------- |:-------------:|
| Name | Name of the monkey |
| Generated sentence | Sentence generated by the monkey |
| Generated amount | Number of sentences generated |
| Elapsed time | How long it took for the monkey to generate the sentence |
