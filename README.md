## Command-line Interface (CLI)

### Markdown
https://www.markdownguide.org/basic-syntax/

### GNU Bash manual
https://www.gnu.org/software/bash/manual/

### Comandos
* **man** - Manual ou execução de ajuda para comandos.
    * Ex.: **man ls** (mostrar informações para o comando "ls")
* **pwd** - Exibir o caminho completo do diretório atual.
* **cd**  - Navegar entre diretórios.
    * .. (voltar)
    * \ (definir espaços no nome do diretório) Ex.: cd arquivo\ morto
* **ls** - Listar conteúdos do diretório.
    * -a (todos o conteúdo - incluindo arquivos ocultos)
    * -l (mais informações)
* **file** - Exibir informções sobre o arquivo (extensão e detalhes).
    * Ex.: file README.md
* **stat** - Exibir informções sobre o arquivo (dono e modificações).
    * Ex.: file README.md
* **mkdir** - Criar diretórios.
    * -p (definir a criação de subdiretórios em simultâneo com o diretório principal)
        * Ex.: mkdir -p tree/dir1 tree/dir2
    * \ (definir espaços no nome do diretório) Ex.: cd arquivo\ morto
* **touch** - Criar arquivos e/ou alterar data e hora de modificação.
    * Ex.: touch index.html
* **cp** - Copiar arquivos (e/ou diretórios).
    * Ex.: cp imagem_01 imagem_02 imagens
    * -r (recursivo - permite copiar diretórios)
* **mv** - Mover ou renomear (arquivos e/ou diretórios).    
    * Ex.: mv imagem_01 imagem_02 imagens
* **rm** - Remover arquivos (e/ou diretórios).
    * -r (recursivo - permite remover diretórios)
    * -f (forçar)
* **rmdir** - Remover diretórios.
    * Ex.: rmdir tree    
* **wildcards** - Curingas para nomes de arquivos/diretórios.
    * \* (asterístico - uma ou várias posições)
    * ? (interrogação - uma posição)
    * Ex.: rm imag* (remove as pastas/arquivos com as iniciais 'imag')