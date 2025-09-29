# C++ Kata Challenge Setup
This is the alpha version of my setup to develop, test, and run katas in a few steps, using Bazel as a build system

## 🚀 How to run it?

Simple and easy... check... <br/>

> I suppose you have already installed Bazel 🤔. If not, pls check the official docs: [https://bazel.build/install](https://bazel.build/install)

I'm gonna give you the *3 simple steps*:

1. Code your kata in the main.cc file
```cpp
#inlcude <iostream>

auto main() -> int
{
  std::cout << "My Awesome Solution\n";
  return 0;
}
```

2. Build
```sh
bazel build //:kata-challenge
```

3. Run
```sh
bazel run //:kata-challenge
```

You can even do both, with one single shell line
```sh
bazel build //:kata-challenge ; bazel run //:kata-challenge
```

## 👥 Collaborations
Any kind of collaboration is very welcome! <br/>

<sub>Happy Coding!</sub>

