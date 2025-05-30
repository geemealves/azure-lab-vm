# Lab Azure - Criação de Máquina Virtual (VM)

Este repositório foi criado como parte do desafio proposto no curso **Microsoft +50 anos: Computação em Nuvem com Azure**, disponível na plataforma [DIO](https://dio.me).

O objetivo é documentar, com resumos, anotações e dicas, a experiência prática de criar e configurar uma máquina virtual na plataforma Azure.

---

## 🧠 Aprendizados

### ☁️ Conceitos de Computação em Nuvem
- Entendimento do que é computação em nuvem e suas vantagens: escalabilidade, disponibilidade, segurança e economia.
- Diferença entre modelos IaaS, PaaS e SaaS — foco do laboratório em **IaaS (Infraestrutura como Serviço)**.

### 💻 Introdução ao Azure
- Criação de conta gratuita na plataforma Azure.
- Navegação pelo **portal.azure.com**.
- Criação de **Resource Group** e familiarização com os principais serviços do Azure.

---

## 🛠️ Passos para Criar uma Máquina Virtual no Azure

1. Acesse o portal do Azure: [https://portal.azure.com](https://portal.azure.com)
2. No painel inicial, clique em **"Máquinas Virtuais"** > **"Criar"** > **"Máquina Virtual"**
3. Configure os seguintes campos:
   - **Subscription:** (sua assinatura ativa)
   - **Resource Group:** criar ou selecionar um existente
   - **Nome da VM**
   - **Região:** ex: "Brazil South"
   - **Imagem:** Windows 11 ou Ubuntu
   - **Tamanho:** selecione um tamanho gratuito ou de baixo custo (ex: B1s)
   - **Usuário e senha de administrador**
4. Em "Configurações de disco", selecione SSD padrão ou HDD (dependendo do uso).
5. Nas opções de **Rede**, certifique-se de permitir o tráfego RDP (Windows) ou SSH (Linux).
6. Revise e crie a máquina.

---

## 📌 Dicas Importantes

- Utilize o **Azure Learn** para tutoriais passo a passo ([link oficial](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)).
- Use o tamanho **B1s** para economizar recursos da conta gratuita.
- Ao terminar de usar a VM, **pare** ou **exclua** para evitar cobrança de créditos.

---

## 🖼️ Capturas de Tela

Se desejar incluir imagens:
- Crie uma pasta chamada `/images`
- Adicione prints da criação da VM, painel do Azure etc.
- Insira assim no README:
