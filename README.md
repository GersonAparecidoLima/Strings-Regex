🔤 Java String Master: Manipulação e Regex

Este repositório reúne implementações práticas para o processamento de textos em Java, cobrindo desde transformações básicas até buscas complexas utilizando Expressões Regulares (Regex).

🚀 O que este projeto aborda
🛠️ Transformação e Análise de Textos
Uso intensivo dos métodos da classe String para limpar e adaptar dados:

trim(): Remoção de espaços em branco desnecessários.

toLowerCase() / toUpperCase(): Padronização de caixa alta e baixa.

replace(): Substituição de caracteres ou sequências de texto.

contains(): Verificação de existência de sub-strings em um texto.

📍 Extração e Acesso Direto
Índices: Acesso a caracteres individuais em posições específicas.

substring(): Recorte preciso de partes de um texto com base em índices iniciais e finais.

🎭 Formatação Avançada
Implementação de strings dinâmicas utilizando especificadores de formato para maior clareza e controle:

%s: Strings | %d: Números inteiros | %f: Números decimais.

%.2f: Controle de precisão para casas decimais.

%n: Quebra de linha independente do sistema operacional.

🔍 Expressões Regulares (Regex)
Uso das classes Matcher e Pattern para interações avançadas:

matches(): Validação se o texto completo segue um padrão.

find() / group(): Localização e extração de trechos específicos (como CPFs, e-mails ou datas).

replaceAll(): Substituições em massa baseadas em padrões complexos.

💻 Tecnologias Utilizadas
Linguagem: Java 17+

Pacotes: java.lang.String, java.util.regex

📖 Exemplos Práticos Incluídos
Sanitização de Inputs: Limpeza de nomes e e-mails de usuários.

Formatador de Relatórios: Uso de printf e String.format para gerar tabelas no console.

Validador de Padrões: Uso de Regex para garantir que entradas de dados sigam formatos específicos.
