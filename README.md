# stack-internal-lib-bug

```
➜  stack-internal-lib-bug git:(master) stack clean; stack build
stack-internal-lib-bug-0.1.0.0: configure (lib)
Configuring stack-internal-lib-bug-0.1.0.0...
stack-internal-lib-bug-0.1.0.0: build (lib)
Preprocessing library for stack-internal-lib-bug-0.1.0.0..
Building library for stack-internal-lib-bug-0.1.0.0..
[1 of 2] Compiling Paths_stack_internal_lib_bug ( .stack-work/dist/x86_64-linux/Cabal-2.0.1.0/build/autogen/Paths_stack_internal_lib_bug.hs, .stack-work/dist/x86_64-linux/Cabal-2.0.1.0/build/Paths_stack_internal_lib_bug.o )
[2 of 2] Compiling Src              ( src/Src.hs, .stack-work/dist/x86_64-linux/Cabal-2.0.1.0/build/Src.o )
stack-internal-lib-bug-0.1.0.0: copy/register
Installing library in /home/dkr/stack-internal-lib-bug/.stack-work/install/x86_64-linux/lts-11.7/8.2.2/lib/x86_64-linux-ghc-8.2.2/stack-internal-lib-bug-0.1.0.0-EJPuQKWbD9EGKGX2UogTFq
Installing internal library b in /home/dkr/stack-internal-lib-bug/.stack-work/install/x86_64-linux/lts-11.7/8.2.2/lib/x86_64-linux-ghc-8.2.2/stack-internal-lib-bug-0.1.0.0-CBrCaGJ7nHiWfBqr28KO5-b
Cabal-simple_mPHDZzAJ_2.0.1.0_ghc-8.2.2: Error: Could not find module: B with
any suffix: ["hi"] in the search path:
[".stack-work/dist/x86_64-linux/Cabal-2.0.1.0/build/b"]
Cabal-simple_mPHDZzAJ_2.0.1.0_ghc-8.2.2:
'/home/dkr/.stack/programs/x86_64-linux/ghc-8.2.2/bin/ghc' exited with an
error:
<command line>: Could not find module ‘B’
Use -v to see a list of the files searched for.

--  While building custom Setup.hs for package stack-internal-lib-bug-0.1.0.0 using:
      /home/dkr/.stack/setup-exe-cache/x86_64-linux/Cabal-simple_mPHDZzAJ_2.0.1.0_ghc-8.2.2 --builddir=.stack-work/dist/x86_64-linux/Cabal-2.0.1.0 register
    Process exited with code: ExitFailure 1

➜  stack-internal-lib-bug git:(master) stack --version
Version 1.8.0, Git revision c435a3cf38ea2bd33a53819893415c1f1a4c4183 x86_64 hpack-0.28.2

```
