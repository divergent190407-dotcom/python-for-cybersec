
```python
name = "Prachi"
```

Here:

* `name` → variable name
* `"Prachi"` → value stored inside it

You can print it:

```python
name = "Prachi"
print(name)
```

Output:

```text
Prachi
```

---

# Data Types

Python stores different kinds of data.

## 1. String (`str`)

Text is called a string.

```python
name = "Prachi"
website = "google.com"
```

Cybersecurity examples:

```python
target = "scanme.nmap.org"
ip = "192.168.1.1"
```

Check type:

```python
print(type(target))
```

Output:

```text
<class 'str'>
```

---

## 2. Integer (`int`)

Whole numbers.

```python
port = 80
age = 19
```

Cybersecurity examples:

```python
ssh_port = 22
http_port = 80
https_port = 443
```

```python
print(type(port))
```

Output:

```text
<class 'int'>
```

---

## 3. Float (`float`)

Numbers with decimals.

```python
cgpa = 8.5
temperature = 36.7
```

```python
print(type(cgpa))
```

Output:

```text
<class 'float'>
```

---

## 4. Boolean (`bool`)

Only two values:

```python
True
False
```

Example:

```python
is_open = True
```

Cybersecurity example:

```python
port_open = False
```

```python
print(type(port_open))
```

Output:

```text
<class 'bool'>
```

---

# Printing Variables

```python
name = "Prachi"
port = 80

print(name)
print(port)
```

Output:

```text
Prachi
80
```

---

# Multiple Variables

```python
target = "scanme.nmap.org"
port = 80
service = "HTTP"

print(target)
print(port)
print(service)
```

---

# f-Strings (Very Useful)

Instead of:

```python
name = "Prachi"
print("Hello " + name)
```

Use:

```python
name = "Prachi"
print(f"Hello {name}")
```

Output:

```text
Hello Prachi
```

Cybersecurity example:

```python
target = "192.168.1.1"
port = 22

print(f"Scanning {target} on port {port}")
```

Output:

```text
Scanning 192.168.1.1 on port 22
```

---

# Taking User Input

```python
name = input("Enter your name: ")
print(name)
```

If user enters:

```text
Prachi
```

Output:

```text
Prachi
```

---

# Important Thing About Input

Everything from `input()` comes as a string.

```python
port = input("Enter port: ")

print(type(port))
```

Output:

```text
<class 'str'>
```

Convert to integer:

```python
port = int(input("Enter port: "))
```

Now:

```python
print(type(port))
```

Output:

```text
<class 'int'>
```

---

# Mini Cybersecurity Example

```python
target = input("Enter target IP: ")
port = int(input("Enter port: "))

print(f"Target: {target}")
print(f"Port: {port}")
```

Example run:

```text
Enter target IP: 192.168.1.1
Enter port: 22

Target: 192.168.1.1
Port: 22
```

---

# Practice Tasks

### Task 1

Create:

```python
name = "Prachi"
college = "IIIT Vadodara"
year = 2
```

Print all three.

---

### Task 2

Create:

```python
target = "scanme.nmap.org"
port = 80
```

Print:

```text
Scanning scanme.nmap.org on port 80
```

using an f-string.

---

### Task 3

Ask user:

```python
Enter website:
```

Store it in a variable and print:

```text
Target website is <website>
```

Once you've done these 3 tasks, the next topic should be **Operators (+, -, *, /, ==, !=, >, <)** because they're needed before learning `if` statements and loops.

