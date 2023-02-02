
## Regular Expression
> Each file in this repository holds code that illustrates an essential concept of programming specific to regular expressions. Resources to learn topic:
> [rubular](http://rubular.com/), [regex101.com](https://regex101.com/r/cO8lqs/2), [blog](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

All code in this directory built by using Ruby's Oniguruma library and was tested using [Rubular](https://rubular.com/). Rubular is a Ruby-based regular expression editor. It's a handy way to test regular expressions as you write them.

## Tasks :page_with_curl:

_Note: Each Ruby script in the project matches regular expressions based on an
argument passed to it via the command line._

* **0. Simply matching School**
  * [0-simply_match_school.rb](./0-simply_match_school.rb): Ruby script that
  matches the regular expression `School`.

* **1. Repetition Token #0**
  * [1-repetition_token_0.rb](./1-repetition_token_0.rb): Ruby script that matches
  the regular expression `hbn` with between 2-5 `t`'s in between `hb` and `n`.

* **2. Repetition Token #1**
  * [2-repetition_token_1.rb](./2-repetition_token_1.rb): Ruby script that matches
  the regular expression `hn` with 0 or 1 occurrences of `b` and 0 or 1
  occurrences of `t` in between `h` and `n`.

* **3. Repetition Token #2**
  * [3-repetition_token_2.rb](./3-repetition_token_2.rb): Ruby script that matches
  the regular expression `hbn` with 1 or more `t`'s in between `hb` and `n`.

* **4. Repetition Token #3**
  * [4-repetition_token_3.rb](./4-repetition_token_3.rb): Ruby script that matches the
  regular expression `hbn` with 0 or more `t`'s in between `hb` and `n`.

* **5. Not quite HBTN yet**
  * [5-beginning_and_end.rb](./5-beginning_and_end.rb): Ruby script that matches a
  regular expression starting with `h` and ending with `n` with any single character in between.

* **6. Call me maybe**
  * [6-phone_number.rb](./6-phone_number.rb): Ruby script that matches a regular expression
  representing a 10-digit phone number.

* **7. OMG WHY ARE YOU SHOUTING?**
  * [7-OMG_WHY_ARE_YOU_SHOUTING.rb](./7-OMG_WHY_ARE_YOU_SHOUTING.rb): Ruby script that
  matches regular expressions of uppercase letters.

* **8. Textme**
  * [100-textme.rb](./100-textme.rb): Ruby script that runs statistics on TextMe app text
  message transcations.
  * Output: `[SENDER],[RECEIVER],[FLAGS]` where
    * `[SENDER]` is the sender phone number or name (including country code
    if present).
    * `[RECEIVER]` is the receiver phone number or name (including country code
    if present).
    * `[FLAGS]` is the flags that were used.
  
## Environment
* CLI
* Language: Ruby
* OS: Ubuntu 14.04 LTS
* Usage: Run each file with ```./[filename] "pattern to test if match" | cat -e```
* Each file has the following format:
```
#!/usr/bin/env ruby
puts ARGV[0].scan(/ regex here /).join
```

## Getting Started
- clone the repository
`git clone git@github.com:selma-belhadj/alx-system_engineering-devops.git`
- navigate to the folder
`cd alx-system_engineering-devops`
- navigate to the concerned folder
  `cd 0x06-regular_expressions`

## Authors
👤 **Selma Belhadj**
- GitHub: [@selma-belhadj](https://github.com/selma-belhadj)
- Twitter: [@Bel_Selma16](https://twitter.com/selma_bel_hadj)
- LinkedIn: [@selma-belhadj](https://www.linkedin.com/in/selma-belhadj/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/selma-belhadj/alx-system_engineering-devops/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

All work contained in this project was completed as part of the curriculum for the ALX-SE programme. ALX Africa is an online full-stack software engineering program that prepares students for careers in the tech industry using project-based peer learning. For more information, visit [this link](https://www.alxafrica.com//).
<p align="center">
  <img src="http://www.alxafrica.com/wp-content/uploads/2022/01/header-logo.png"
    alt="ALX Africa Logo">
</p>
