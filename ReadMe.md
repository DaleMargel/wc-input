# **wc-input**
> an &lt;input&gt; tag on steroids

This extends the input tag
- supports all common &lt;input&gt; attributes
- adds more useful features
- fairly light weight, just over 4kb
- will flash green when being updated
- detects errors and displays yellow when found
- renders as simple text when printing

## Usage
Additional attributes
| Attribute | Meaning |
| --------- | ------- |
| span="narrow" | sets width to 75px |
| span="normal" | (default) sets width to 150px |
| span="wide" | sets width to 225px |
| span="extrawide" | sets width to 300px |
| pattern=regex | normal input behaviour |
| pattern="int" | enforces an integer |
| pattern="+int" | enforces a positive integer |
| pattern="-int" | enforces a negative integer |
| pattern="float" | enforces a float |
| pattern="+float" | enforces a positive float |
| pattern="-float" | enforces a negative float |
| fix=int | rounds number of decimal points |
| fix=-int | rounds number of powers of 10 |
<br>

## Demo
Use this link : <https://dalemargel.github.io/wc-input>
