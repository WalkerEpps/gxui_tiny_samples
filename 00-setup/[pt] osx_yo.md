# 1. Primeiro Passo

Meu ambiente:  
OSX yosemite 10.10.3  
Golang 1.4.2

Adicione no **"~/.bash_profile"** abaixo.
Não sei porque mas **não funcionou addicionando no ".bashrc"**
```
export GOPATH=$HOME/Documents/go
export PATH=$PATH:$GOPATH/bin
```

Reinice ou digite o código para reiniciar  
```
> source ~/.bash_profile
```

# 2. Instalar o gxui

É bom instalar nessa ordem porcausa da dependência.
```terminal
brew install glew
go get http://code.google.com/p/freetype-go/freetype/raster
go get code.google.com/p/freetype-go/freetype/truetype
go get github.com/go-gl/gl/v3.2-core/gl
go get github.com/go-gl/glfw/v3.1/glfw
go get github.com/google/gxui
```


# 3. Baixar as fonters
[SourceCodePro](https://www.google.com/fonts#UsePlace:use/Collection:Source+Code+Pro)

# 4. Os Oficiais
```
go install github.com/google/gxui/samples/...
```

# # Sites
[gxui on GitHub](https://github.com/google/gxui)  
[gxui/sample  on GitHub](https://github.com/google/gxui/tree/master/samples)  
[go-gl/gl on GitHub](https://github.com/go-gl/gl)  
[go-gl/glfw on GitHub](https://github.com/go-gl/glfw)  
[go-gl/examples on GitHub](https://github.com/go-gl/examples)  
