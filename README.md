# Go Email Analyzer CLI (WIP)
**This is work in progress**

We are about to work on this repo.

Analyze your suspicious emails and extract headers, links and hashes.


## usage: 

1. build the project: 

    ```Make
    make build
    ```

2. Prepare the **eml** file (Email clients support exporting emails in the eml format) 
3. run the **CLI**
    ```
    ./bin/mailp parse -f <example.eml> --content
    ```

    To see all the availables commands, run:  

    ```
    ./bin/mailp parse --help
    ```
