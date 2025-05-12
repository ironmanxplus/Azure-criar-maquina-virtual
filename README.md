# Azure-criar-maquina-virtual
1 - Acessar https://portal.azure.com/

2 - Criar um grupo de recursos ( O grupo de recursos ajuda a organizar a conta, portanto conforme o cresccimento da rede é essencial)
    Clicar em Grupo De Recursos
    Criar
    Neste momento voce irá dar um nome ao grupo (FINANCEIRO, RH) e escolher a região (o ideal é Brazil South)
    Clicar em Revisar + Criar e depois CRIAR

3 - Criando a Maquina Virtual
    Buscar por "Maquinas Virtuais"
    Clicar em +CRIAR  e maquina Virtual Azure

 4 - Configurando a VM
** Assinatura	    ===== Selecione sua assinatura ativa
** Nome da VM	    ===== Utilizar um nome que te ajudará a identificar a VM posteriormente
** Região	        ===== Brazil South 
** Disponibilidade=====	Deixe padrão, ou configure zona/instância reservada
** Imagem	        ===== Escolha o SO: Dependendo da sua necessidade
** Tipo de segurança	= Deixe como Standard
** Tamanho	      ===== Clique em "Alterar tamanho" e escolha conforme necessidade.(Quanto maior o tamanho maior o valor da cobrança)
** Nome de usuário	==  Usuário da VM (ex: azureuser)
** Autenticação	   ==== Senha ou Chave SSH (senha é mais simples para testes)
** Porta de entrada pública	Permitir porta selecionada
** Porta a permitir	=== RDP (3389) para Windows ou SSH (22) para Linux

Depois clique em Proximos Discos
Disco do SO == SSD Premium

Rede
Interface de Rede Virtual = Vai ser criado automaticamente
IP Publico == SIM
Grupo de Segurança = pode adicionar
Porta 3389 aberta

Gerenciamento
Diagnostico de Inicialização == ATIVAR
Identity  == PADRÂO

Avançado
Nâo precisar mexer

TAGS
As TAGS pode ajudar a identifcar de qual area é a VM ou para fins de cobrança

Revisar e Criar

Após efetuar a criação a VM levará alguns minutos para subir

