<h1 align="center">Welcome to jmeter 👋</h1>
<center>

![Hulo](https://img.shields.io/badge/Hulo-%238866E9.svg?logoColor=white&style=for-the-badge) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)

</center>

---

English | [简体中文](./README.zh-CN.md)

> This is an experimental project that aims to rewrite the original bash scripts in the [jmeter](https://github.com/apache/jmeter) source code using the [Hulo](https://github.com/hulo-lang) language.
> By transforming imperative shell scripts into declarative Hulo code, the project explores modern script practices and maintainability.

## 🚀 Getting Started

> [!WARNING]
> This project is in an early stage and may have incomplete functionality, performance issues, or compatibility problems. It is not recommended for production use.

### Clone and Build

```sh
git clone https://github.com/hulo-lang/jmeter.git

cd jmeter

hulo build .
```

### Test Data

The `testdata` directory contains original script files extracted from the jmeter repository, serving as translation references for Hulo.

## 🤝 Contributing

We welcome all kinds of contributions, including but not limited to:

* Reporting bugs
* Submitting issues or feature requests
* Translating or rewriting scripts
* Sending pull requests

Please check the [issues page](https://github.com/hulo-lang/jmeter/issues) and follow the contribution guidelines.

## 📝 License

This project is licensed under the Apache-2.0 license, see [LICENSE](LICENSE) for details.