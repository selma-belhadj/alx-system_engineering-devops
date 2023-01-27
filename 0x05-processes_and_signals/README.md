# Loops, conditions and parsing
> Each file in this repository holds code that illustrates an essential concept of system engineering and devOps pertaining to processes and signals: `ps`, `pgrep`, `kill`, `pkill`, `SIGINT` (Ctrl-C), SIGTERM(`kill`), `SIGQUIT`(Ctrl-|)

### Description of what each file shows:

- Files that start with:
1. display bash script's pid
2. list processes
3. display pid's related to bash using ps
4. display pid's related to bash using pgrep
5. create infinite loop with sleep 2 that Ctrl-C can kill
6. script to kill file 4 in different terminal
7. script to pkill file 4 in different terminal
8. upgrade file 4 to catch Ctrl-C SIGINT and display message instead .67 script to kill file 7 in different terminal and gets caught
9. script to pkill file 7 successfully
   -  infinite loop that can be killed with Ctrl-C
   -  infinite loop with multiple signal catches and ultimately exits
   -  creates 5 zombie processes

### Built with
* CLI
* Bash scripts
* OS: Ubuntu 14.04 LTS
* Executable: chmod +x [filename]; run with ./[filename]
* Style guidelines: [Shellscript for Bash](https://github.com/koalaman/shellcheck)

## Getting Started

- clone the repository
`git clone git@github.com:selma-belhadj/alx-system_engineering-devops.git`
- navigate to the folder
`cd alx-system_engineering-devops`
- navigate to the concerned folder
  `cd 0x05-processes_and_signals`
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
