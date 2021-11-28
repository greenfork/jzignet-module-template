# Jzignet module template

Template for building [Janet](https://janet-lang.org/) modules with
[Zig](https://ziglang.org/) with the help of
[Jzignet](https://github.com/greenfork/jzignet).

Requires Zig version of at least 2021-11-20, zig executable must be in PATH.
You can download the latest Zig build from <https://ziglang.org/download/>.
You will also need Janet and jpm installed on your system
<https://github.com/janet-lang/janet/releases>.

## How to use

1. Clone this repository with submodules:
   ```shell
   $ git clone --recursive https://github.com/greenfork/jzignet-module-template
   ```
2. Change all files however your like.
3. Try building it:
   ```shell
   $ jpm build
   ```
4. Push your repository online.
5. Use your repository link as a dependency in `project.janet` file.

See
[example](https://github.com/greenfork/jzignet/tree/master/examples/zig_module)
of using this template. Also source code is heavily commented.

If you want to clear git history after cloning this repository, just
re-initialize git repository:
```shell
$ rm -rf .git
$ git init .
```

## License

MIT, see LICENSE file.
