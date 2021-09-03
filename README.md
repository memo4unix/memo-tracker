# Welcome to memo's issue tracker!

You can use it to request features and file bugs, but also for general discussion (if you like). [Click here](https://github.com/memo4unix/memo-tracker/issues) (or on the "Issues" link nearly at the top) to see all issues.

Issues are prioritised by the number of votes they receive. You can vote using [GitHub's Reactions feature](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments).

This page is still in an early stage. Feedback is highly appreciated! If you have ideas or suggestions for improvements, please [open an issue](https://github.com/memo4unix/memo-tracker/issues/new).

# memo
- **MEMO**rize all your ubuntu/mac command lines and share them with colleagues.
- A powerful python history tool using google sheet...
- btw, no need root permission to install this tool..

### **Download**
download the **memo_1.0.XX.tar.gz** file

### **UnZip**
`Open when done`

or

`tar -xvf memo_1.0.XX.tar.gz`

### **Installation**
1. `cd  memo_1.0.XX`
2. `. remove_memo.sh `(remove previous version)
3. `. install_memo.sh`

### **Setup**
During installation you will get this question
**Please enter your email or enter for default:**
- if you want to share your command lines with colleagues enter your **cie** email
- if you **don't** want to share your command lines with collegues enter your **private** email
- the default email is generally the **cie** email, if you have a doubt enter your **cie** email

### **Alias**
- An alias **memo** is created which allow to call it anywhere from any terminal
- An alias **mm** is **also** created in case of **multimail** is not already installed

### **Usage**

- `memo` will display all history from all your console terminals
- `memo [pattern]` will display all your history containing this pattern, for example `memo ls`
- `memo [n]` will execute the index command line - Refer to command line n, for example `memo 5`
- `memo [pattern] [-e email]` will display history of your colleague identified by email, for example `memo ls -e scott.tiger@cisco.com` will display all command lines of **scott** which contains the pattern `ls`


