[![Chat at https://gitter.im/python/typing](https://badges.gitter.im/python/typing.svg)](https://gitter.im/python/typing?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Static Typing for Python

## Documentation and Support

The documentation for Python's static typing can be found at
[typing.readthedocs.io](https://typing.readthedocs.io/). You can get
help either in our [support forum](https://github.com/python/typing/discussions) or
chat with us on [Gitter](https://gitter.im/python/typing).

Improvements to the type system should be discussed on the
[typing-sig](https://mail.python.org/mailman3/lists/typing-sig.python.org/)
mailing list, although the [issues](https://github.com/python/typing/issues) in this
repository contain some historic discussions.

## Repository Content

This GitHub repository is used for several things:

- The documentation at [typing.readthedocs.io](https://typing.readthedocs.io/)
  is maintained in the [docs directory](./docs).

- A [discussion forum](https://github.com/python/typing/discussions) for typing-related user
  help is hosted here.

Historically, this repository also hosted:

- The `typing_extensions` package, which now lives in the
  [typing_extensions](https://github.com/python/typing_extensions) repo.
  It used to be in the `typing_extensions` directory.

- A backport of the
  [`typing` module](https://docs.python.org/3/library/typing.html) for older
  Python versions. It was removed after all Python versions that lack `typing`
  in the standard library reached end of life. The last released version,
  supporting Python 2.7 and 3.4,
  is [available at PyPI](https://pypi.org/project/typing/).
