# slang-kernel-test

## Transpile

### GLSL

``` bash
# stage is the shader type annotation and entry is the function name
slangc -target glsl -stage compute -o test.glsl test.slang -entry computeMain
```