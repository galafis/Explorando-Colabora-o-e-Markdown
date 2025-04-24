# Guia rápido: Como colaborar com um projeto no GitHub

1. Acesse o repositório que deseja contribuir.
2. Clique em `Fork` no canto superior direito.
3. Vá até sua conta e clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/repositorio.git
   ```
4. Crie uma nova branch:
   ```bash
   git checkout -b nova-feature
   ```
5. Faça suas alterações, adicione e faça commit:
   ```bash
   git add .
   git commit -m "Minha contribuição"
   ```
6. Envie para o repositório remoto:
   ```bash
   git push origin nova-feature
   ```
7. Volte ao GitHub e clique em "Compare & Pull Request".
