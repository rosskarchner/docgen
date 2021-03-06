Docgen
=====================

Transform your postman collection to html documentation

![Task screenshot](screenshot.png)

### Installation
```go
go get -u github.com/thedevsaddam/docgen
```

[Download binary](https://github.com/thedevsaddam/docgen-bin)

### Available features
* Live postman collection to documentation
* Build postman collection to html documentation

### Usage
* To see live documentation from postman collection use `docgen server -f input-postman-collection.json -p 8000` This will open the html version of postman collection to the defined port
* To build a documentation use `docgen build -i input-postman-collection.josn -o ~/Downloads/index.html`

### Author
1. [Sajib Sikder](https://github.com/mhshajib)
1. [Saddam H](https://github.com/thedevsaddam)

### Contribution
Your suggestions will be more than appreciated.
[Read the contribution guide here](CONTRIBUTING.md)

### See all [contributors](https://github.com/thedevsaddam/docgen/graphs/contributors)

### **License**
The **docgen** is an open-source software licensed under the [MIT License](LICENSE.md).
