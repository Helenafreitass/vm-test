# vm-test

# 💻 Máquinas Virtuais (VMs) no Microsoft Azure  

## 🔍 Introdução  
As **VMs Azure** são serviços de computação em nuvem que permitem executar sistemas operacionais e aplicações sob demanda.  
**Casos de uso comuns**:  
- Hospedagem de aplicações web.  
- Ambientes de desenvolvimento/testes.  
- Processamento de dados.  

## 🛠️ Como Criar uma VM no Azure  
### Passos Básicos (Portal Azure):  
1. Acesse o [Portal Azure](https://portal.azure.com).  
2. Clique em **"Criar um recurso"** > **"Máquina Virtual"**.  
3. Preencha:  
   - **Assinatura** e **Grupo de Recursos**.  
   - **Nome da VM**, **Região**, e **Imagem (ex: Ubuntu Server 20.04 LTS)**.  
4. Configure tamanho (SKU), credenciais e regras de rede (NSG).  
5. Revise e clique em **"Criar"**.  


## ⚠️ Melhores Práticas  
- **Segurança**: Use NSGs (Network Security Groups) para filtrar tráfego.  
- **Custos**: Desligue VMs não utilizadas ou opte por Spot VMs para economizar.  
- **Backup**: Configure o Azure Backup para evitar perda de dados.  

## 📚 Recursos Adicionais  
- [Documentação Oficial Azure VMs](https://learn.microsoft.com/pt-br/azure/virtual-machines/)  
- [Calculadora de Custos Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)  

