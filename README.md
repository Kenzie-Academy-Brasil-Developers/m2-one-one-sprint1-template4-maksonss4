![>>> Abra esse README.md no modo de 'Preview' para melhor visualização <<<](assets/20220719_104823_CodeIgualUmKenzie.png)

# Instruções

Esse teste tem como objetivo **fixar seus conhecimentos sobre o assunto abordado nessa última semana**.

Esse projeto possui todos os arquivos necessários para desenvolver a solução esperada, então **NÃO SERÁ NECESSÁRIO CRIAR OUTROS ARQUIVOS**.

### ⏱️ Duração do teste

> `15 minutos para todo o desenvolvimento`

### ✅ Console.log

> `Será permitido usar o console.log() para testar o seu código`

# Problema

Você terá um **array de objetos** chamado `noticias` **já predefinido** no arquivo `script.js`.

Dentro dele terão objetos contendo as seguintes chaves:

- `manchete` - Tipo **String**
- `corpo` - Tipo **String**
- `local` - Tipo **String**
- `data` - Tipo **String**
- `img` - Tipo **String**

### 🎲 Desafio

Dadas essas informações, será necessário desenvolver:
1. Criar uma função chamada `removerNoticiaVelha`, essa função deve:
   - Buscar a div com o id **noticia_velha** usando o DOM;
   - Remover essa div usando o DOM

2. Criar uma função chamada `listarNoticias`, essa função deve:
   - buscar a tag `main`, que possui o id **main**, utilizando JS;
   - Criar algum laço de repetição que percorre o array `noticias`;
   - Em cada iteração deverá ser feita uma verificação e a criação da estrutura da notícia:
      - A verificação será, **se** a notícia foi publicada no dia **18/07/2022** **e** o local for **Curitiba/PR**, essa notícia deve receber uma **classe** chamada **border** na sua `div` que encapsula o conteúdo;
      - A estrutura, por sua vez, deverá ser a seguinte:
         - Crie uma `div` para encapsular o conteúdo;
         - Crie uma tag `h2` que deve conter o valor **manchete** da notícia;
         - Crie Uma tag `h3` que deve conter o valor **local** da notícia;
         - Crie Uma tag `p` que deve conter o valor **corpo** da notícia;
         - Crie Uma tag `p` que deve conter a valor **data** da notícia;
            - Adicione a classe **date** ao paragrafo referente a data
         - Crie Uma tag `img` que deve ter como `src` o valor **img** da noticia e o `alt` com o valor **manchete** da notícia.
         - Adicione todos os itens dentro da div seguindo a ordem acima.
       
   - Ao fim de cada iteração do loop deverá ser feito um append na tag `main` com a div pronta e seus valores.
   - Por fim, chame as funções.
   

---

> **Bom desenvolvimento**, e qualquer dúvida só perguntar ao seu aplicador 😉!
