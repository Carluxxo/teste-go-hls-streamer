# Use a imagem oficial do Golang
FROM golang:latest

# Defina o diretório de trabalho no container
WORKDIR /app

# Copie os arquivos do projeto para o container
COPY . .

# Compile o aplicativo
RUN go build -o main .

# Exponha a porta 8080
EXPOSE 8080

# Comando para iniciar o aplicativo
CMD ["./main"]
