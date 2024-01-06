# Use uma imagem base do alpine com nginx
FROM nginx:alpine

# Copie o arquivo HTML para o diretório padrão do nginx
COPY player.html /usr/share/nginx/html/

# Expõe a porta 8085
EXPOSE 8085

# Inicia o nginx quando o container é iniciado
CMD ["nginx", "-g", "daemon off;"]
