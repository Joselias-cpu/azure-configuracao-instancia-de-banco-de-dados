# azure-configuracao-instancia-de-banco-de-dados
Resumo do processo de configuração de uma instância de Banco de Dados na plataforma Microsoft Azure
### Uma implantação de Instância Gerenciada de SQL do Azure pode ser implantada usando o portal do Azure, o PowerShell ou a CLI do Azure.
> **Portal:** Etapas:
1. Entre no portal do Azure.
2. No menu esquerdo do portal do Azure, selecione SQL do Azure. Se SQL do Azure não estiver na lista, selecione Todos os serviços e, em seguida, digite SQL do Azure na caixa de pesquisa.
3. Selecione + Criar para abrir a página Selecionar opção de implantação do SQL. Veja mais informações sobre a Instância Gerenciada de SQL do Azure selecionando Mostrar detalhes no bloco Instâncias gerenciadas de SQL.
4. Escolha Instância única na lista suspensa e depois selecione Criar para abrir a página Criar instância Gerenciada de SQL do Azure.
5. **Guia Básico:** Preencha as informações obrigatórias exigidas na guia Básico, que é o requisito mínimo para provisionar uma Instância Gerenciada de SQL.
6. Em Detalhes da instância gerenciada, selecione Configurar instância gerenciada na seção Computação + armazenamento para abrir a página Computação + armazenamento.
7. Depois de designar sua configuração de Computação + Armazenamento, use Aplicar para salvar suas configurações e navegar de volta para a página Criar Instância Gerenciada SQL do Azure. Selecione Próximo para ir para a guia Rede
8. **Guia Rede:** Preencha as informações opcionais na guia Rede. Se você omitir essas informações, o portal aplicará as configurações padrão.
9. Selecione Revisar + criar para revisar suas escolhas antes de criar uma instância gerenciada. Ou defina as configurações de segurança selecionando Avançar: Configurações de segurança.
10. **Guia Segurança:**  deixe as configurações na guia Segurança em seus valores padrão.
11. Selecione Revisar + criar para revisar suas escolhas antes de criar uma instância gerenciada. Ou defina mais configurações personalizadas selecionando Avançar: configurações adicionais.
12. **Configurações Adicionais:** Preencha as informações opcionais na guia Configurações adicionais. Se você omitir essas informações, o portal aplicará as configurações padrão.
13. Selecione Revisar + criar para revisar suas escolhas antes de criar uma instância gerenciada. Ou, então, configure as marcas do Azure selecionando Avançar: Marcas (recomendado).
14. **Marcações:** Adicione marcas aos recursos no modelo do ARM (modelo do Azure Resource Manager) para ajudar você a organizar logicamente seus recursos. <br/> Considere marcar a nova Instância Gerenciada de SQL com a marca Proprietário para identificar quem a criou e a marca Ambiente para identificar se esse sistema é de produção, desenvolvimento etc. Selecione Examinar + criar para prosseguir.
16. **Exaaminar e Criar:** Selecione a guia Examinar + criar, examine suas escolhas e selecione Criar para implantar sua instância gerenciada.
> **PowerShell:** Etapas:
1. Primeiro, defina suas variáveis; 
2. Depois, crie seu grupo de recursos;
3. Depois disso, crie sua rede virtual;
4. Finalmente, crie sua instância;
5. **Revisar as Revisar configurações de rede:**
6. Selecione o recurso Tabela de rotas em seu grupo de recursos para examinar o objeto padrão de tabela de rotas definido pelo usuário e as entradas para rotear o tráfego de dentro da rede virtual da Instância Gerenciada de SQL.
7. **Criar banco de dados** usando o portal do Azure, o PowerShell ou a CLI do Azure.
8. **Recuperar detalhes da conexão para a Instância Gerenciada de SQL**
>** CLI do Azure**
1. Defina suas variáveis; 
2. Depois, crie seu grupo de recursos;
3. Crie sua rede virtual;
4. Crie sua instância;
5. **Revisar as Revisar configurações de rede:**
6. Selecione o recurso Tabela de rotas em seu grupo de recursos para examinar o objeto padrão de tabela de rotas definido pelo usuário e as entradas para rotear o tráfego de dentro da rede virtual da Instância Gerenciada de SQL.
7. **Criar banco de dados** usando o portal do Azure, o PowerShell ou a CLI do Azure.
8. **Recuperar detalhes da conexão para a Instância Gerenciada de SQL**
