<img width="1089" height="957" alt="image" src="https://github.com/user-attachments/assets/3af3c0a2-4dd5-4d55-a88c-9abc428cc14f" />erlang_test_runner
=====

An escript

Build
-----

    $ rebar3 escriptize

Run
---

    $ _build/default/bin/erlang_test_runner



## Running Tests Locally

To run the full test suite locally, you need to have [Docker](https://www.docker.com/) installed.

Additionally, the `SOURCE_PATH` environment variable must point to the root of the cloned repository. On Linux/macOS, you can run the tests using the following command:

```bash
SOURCE_PATH=$(pwd) rebar3 ct
