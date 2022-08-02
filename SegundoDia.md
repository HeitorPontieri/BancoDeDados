 # SGBD
   |> Sistema Gerenciador de Banco de Dados
        |> Gerencia o acesso e a manutenção dos dados arrmazenados 
            |> Tudo passa pelo SGBD
                |> Salva os dados no HD, ligam dados e metadados, encripta dados, ccontrola o acesso, faz um backup caso os dados sejam danificados
                    |> É o "sistema operacional" do banco de dados, sem ele nada funciona

    ** Regrinhas de SGBD

        - Auto-Contennção 
            |> Organiza e junta os dados para eles voltarem completos, organização dos dados
        
        - Inddependência dos dados
            |> A modelagem do banco NUNCA pode ser acessada ou modificada por software externo ou usuário

        - Abstração de dados
            |> o usuario não pode ter acesso direto ao banco de dados

        - Visões
            |> Cada usuário pode exigir ou mesmo precisar de uma visão diferenciada da base de dados, é a forma que cada um pode manipular o banco de dados
        
        - Transações
            |> Controle de concorrência , ou seja, o acesso ao mesmo dado deve ser de forma controlada e possível de acontecer, o dado pode ser usado por mais de um computador ao mesmo tempo

        - Segurançaa
            |> Segurança de acesso(usuários e aplicações)
            |> Segurança conta falhas (recovery)
            |> Monitoramento de transações, categorias de falhas, manutenção de hi    stórico de atualizações (logs) e backups do BD
        
        - Controle de Redundância 
            |> Não deve haver uma duplicação nos dados, guardar informações repetidas

        - Interfaceamento
            |> Utilização de interface gráfica para auxilinar no desenvolvimento

        - Métodos de acesso
            |> DDL -> Data Definition Language -> especifica e altera a estrutura do banco, pode criar, apagar, modificar a modelagem, cria o espaço para o dado ficar dentro do banco de dados
            |> DML -> Data Manipulation Language -> manipula, processa os dados
            |> DCL -> Data Control Language -> responsavel pelas permissões de acesso ao banco de dados

    ** Vantagens de um SGBD

        - Rapidez na manipulação e no acesso a informação
        - Redução do esforço humano
        - Redução na redundância e a inconsistência de informações
        - Redução de problemas da integridade 
        - Compartilhamento de dados
        - Aplicação automatica de restrições de segurança
        - Controle integrado de informações distribuidas fisicamente
        - Precisão no resultao da informação
        - Maior disponiilidade dos dados
        - Tempo de desenvolvimento reduzido do software