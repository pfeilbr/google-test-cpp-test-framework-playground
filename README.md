# google-test-cpp-test-framework-playground

learn [googletest](https://github.com/google/googletest) / [gtest](https://github.com/google/googletest) C++ test framework

see `README.md` in each subdirectory under [`src`](src)

## gtest install

```sh
# download source
cd ~/dev
curl -LO https://github.com/google/googletest/archive/release-1.8.1.zip
unzip release-1.8.1.zip
cd googletest-release-1.8.1
mkdir build
cd build
cmake ..
make
make install
```