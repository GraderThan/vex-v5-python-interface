# VexV5 Python Interface for IDEs

👋 Hey there, Python enthusiasts and Vex Robotics lovers! Welcome to the GitHub
repository for our Python interface tailored specifically for Vex V5. This
interface isn't your typical fully-functional library. Instead, it is designed
to enrich your programming experience so that smart type-hints and auto-complete
features work within your IDE. 

## Why This Repository?
You're probably wondering, "Why do I need this?" Well, here's the deal:

1. **Type-Hinting & Auto-Completion**: Whether you're using the Greater Than IDE, Visual
   Studio Code, or PyCharm, this interface will help your IDE provide helpful hints and
   suggestions as you type, reducing errors and speeding up your coding process.

2. **Temporary Solution**: Consider this a placeholder, a stepping stone if you
   will. Vex hasn't released their official Python package yet. So, until they
   do, we've got you covered! 


## Getting Started With Grader Than:

After completing these steps your students in your course will have the Official Vex
IDE extension and full IDE support for vex. 

**Prerequisites:** It is assumed you already have a [Grader Than Workspace
setup](https://docs.graderthan.com/workspace/create/). 

1. Create a dependency, see these
   [docs](https://docs.graderthan.com/workspace/config/#create-a-dependency) for
   more details. 
2. Use the code below as your install script for the dependency you created.
   
    ```shell
    # This installs the type-hinting and autocomplete tools
    mkdir -p /tmp/vex
    cd /tmp/vex
    git clone https://github.com/graderthan/vex-v5-python-interface.git
    pip install ./vex

    # This installs the official vex extension
    chmod +x ./ext/install.sh
    ./ext/install.sh

    rm -rf /tmp/vex
    ```

3. **🥳 Done!** Now all your students and your course will have the Official Vex
   IDE extension and with full IDE support.


## Contribution & Feedback
Love this project? Think it could be better? Your contributions and feedback are
what make this community amazing. Feel free to fork, submit pull requests, or
open issues. Let's make this the best temporary solution for all Vex V5 Python
programmers! 

## Acknowledgements
A huge shoutout to everyone in the Python and Vex robotics communities. Your
passion and innovation inspire projects like this. And of course, we're all
eagerly waiting for the official Vex Python package – coming soon, we hope!
