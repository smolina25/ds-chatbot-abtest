# A/B Testing
A/B testing (also known as split testing) is a controlled experiment used to compare two or more versions of a variable—such as a webpage, feature, or algorithm—to determine which performs better according to a defined metric (e.g., click-through rate, conversion rate, retention).

In a typical A/B test:

+ __Version A__ (the control) is compared against __Version B__ (the variant) under similar conditions.
+ Users are randomly assigned to one of the versions.
+ Their interactions are measured and analyzed to identify statistically significant differences.

A/B testing is widely used in product development, marketing, UX design, and data science to make data-driven decisions and optimize user experience without relying on guesswork. 

In this repo you will find a guided example on the case of a chatbot hosted on our website.

## Environment

### **`macOS`** type the following commands :

- Install the virtual environment and the required packages by following commands:

  ```BASH
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```

### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

  For `PowerShell` CLI :

  ```PowerShell
  pyenv local 3.11.3
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
  For `Git-Bash` CLI :

  ```
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```
