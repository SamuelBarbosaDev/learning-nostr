# Learning Nostr

## Implementações

### 1. **Autenticação com Chave Pública**

- **Funcionalidade**: Os usuários devem se autenticar usando chaves públicas e privadas, semelhante ao Bitcoin.
- **NIP-01**: Define os formatos básicos de eventos, incluindo a estrutura necessária para autenticação com chaves públicas e privadas.

### 2. **Envio e Recepção de Mensagens**

- **Funcionalidade**: Implementar a capacidade de enviar e receber mensagens assinadas criptograficamente.
- **NIP-01**: Define os eventos básicos e suas assinaturas, necessários para enviar e receber mensagens.
- **NIP-02**: Aborda a comunicação entre clientes e relays, essencial para enviar e receber mensagens.

### 3. **Seleção de Relays**

- **Funcionalidade**: Permitir que os usuários escolham quais relays (servidores) usar para enviar e receber dados.
- **NIP-01**: Define os detalhes sobre como os eventos devem ser enviados e recebidos pelos relays.
- **NIP-02**: Aborda como clientes se comunicam com múltiplos relays.

### 4. **Validação de Assinaturas**

- **Funcionalidade**: Verificar as assinaturas das mensagens para garantir que são válidas e autênticas.
- **NIP-01**: Especifica como as assinaturas dos eventos devem ser geradas e validadas.

### 5. **Interface de Usuário**

- **Funcionalidade**: Criar uma interface simples para que os usuários possam ler e escrever mensagens.
- **NIP-05**: Propõe um sistema para associar nomes (identidades) amigáveis a chaves públicas, o que pode ser útil na interface de usuário.
- **NIP-06**: Recomendações para a implementação de interfaces de clientes.

### 6. **Integração com Bitcoin**

- **Funcionalidade**: Utilizar a Lightning Network do Bitcoin para transações seguras e rápidas.
- **NIP-07**: Propõe um sistema de pagamentos entre usuários utilizando a Lightning Network do Bitcoin.
