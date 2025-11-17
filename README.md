# Sistema de Gestão de Estoque
Um projeto completo de sistema de gestão de estoque (SGE) focado em um mercado, desenvolvido totalmente em Python. O sistema conta com uma interface gráfica e um banco de dados local para controle total das operações.

<img width="1353" height="717" alt="image" src="https://github.com/user-attachments/assets/cc58e709-dc1b-4d50-96f4-50ed4d4f2783" />


# Funcionalidades
O sistema foi construído com um fluxo de trabalho completo, permitindo ao usuário:

  Dashboard Interativo: Métricas rápidas (custo total, itens totais, estoque baixo) e atalhos para as funções principais.

  Alertas Visuais: Lista de produtos com estoque baixo (com limite configurável) direto na página principal, com botão para "Comprar" imediato.

  Gestão de Produtos (CRUD): Cadastro completo de novos produtos e exclusão de itens.

  Busca e Ordenação Avançada: Uma tela central para listar todos os produtos, com filtros por nome, filtros por categoria e ordenação clicável em qualquer coluna (código, nome, qtd, etc.).

  Movimentação de Estoque: Funções de "Comprar" (Entrada) e "Vender" (Saída) que são acessadas direto pela lista, com atualização em tempo real no banco e na interface.

  Relatórios Gerenciais:

    Gráficos (Matplotlib): Curva ABC, Valor por Categoria e Evolução de Estoque.

    Relatórios (Texto): Cálculo de Custo de Manutenção (pedindo a taxa %) e Giro de Estoque (pedindo o período em dias).

  Banco de Dados: Persistência de dados com SQLite. O script já vem com um gerador de 800 produtos (incluindo exemplos de estoque baixo) para testes.

# Tecnologias Utilizadas
Python 3

Tkinter (para a interface gráfica)

SQLite3 (para o banco de dados local)

Matplotlib (para a geração dos gráficos)

PyInstaller (usado para empacotar o projeto em um .exe)

# Como Executar
Você pode rodar este projeto de duas formas:

## 1. Para Desenvolvedores (Rodando o Script)
Se você tem o Python instalado:

Baixe o arquivo Python e execute no VSCode, o banco de dados será gerado automaticamente

## 2. Para Usuários (Usando o .exe)
O programa foi empacotado usando o PyInstaller.

Baixe a pasta dist/mercado_gui/ (ou o arquivo .zip gerado na seção "Releases" do GitHub).

MUITO IMPORTANTE: O arquivo mercado.db deve estar na mesma pasta que o mercado_gui.exe para que o programa funcione e salve os dados.

Dê dois cliques no mercado_gui.exe para rodar
