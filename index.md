---
title: Política de Privacidade — Corrida Certa
---


**Versão:** 0.7.9-beta  
**Última atualização:** 23 de setembro de 2026  
**Estado:** versão de testes gratuita, sem publicidade e sem cobrança

## 1. Escopo

O **Corrida Certa** ajuda a analisar ofertas visíveis em aplicativos de transporte compatíveis e apresenta cálculos no próprio aparelho. O aplicativo não aceita ou recusa ofertas, não cria conta de usuário e não envia o conteúdo analisado para servidores próprios.

A versão beta é gratuita. Não há assinatura ativa, período de teste pago, publicidade, produto de faturação ou cobrança nesta versão. Uma futura versão comercial somente poderá adicionar preço e condições depois de atualizar o aplicativo, a ficha da loja, a configuração correspondente no Google Play e esta política.

## 2. Dados tratados no aparelho

### Conteúdo visível dos cartões de oferta

Após a pessoa ativar voluntariamente o serviço de Acessibilidade nas configurações do Android, o aplicativo pode ler dados visíveis em cartões de oferta de aplicativos compatíveis selecionados. Esses dados podem incluir valor, moeda, distância, tempo, pontos de recolha e destino, nome exibido, categoria, avaliação e detalhes disponíveis no cartão.

Esses dados são usados localmente para calcular valor por quilómetro, valor por hora e classificação da oferta. Custo e lucro estimados são calculados somente quando a pessoa ativa a opção de custo do veículo. O aplicativo não aceita, recusa ou executa ações nas ofertas.

### Leitura visual opcional

O reconhecimento de texto por imagem é desligado por padrão e exige confirmação separada. Quando ativado, ele captura temporariamente somente a janela visível do aplicativo compatível para reconhecer texto localmente. Em tela dividida, a outra metade não é capturada ou analisada. A imagem temporária é descartada após a leitura, salvo se a pessoa também tiver autorizado a captura automática para a galeria. Conteúdo protegido pelo Android não é contornado.

### Histórico e diagnóstico locais

O histórico guarda uma vez cada oferta reconhecida no banco privado do aparelho. Um registro pode incluir métricas calculadas, detalhes visíveis do cartão e texto disponível. A pessoa pode apagar todo o histórico pela tela Histórico. Eventos repetidos são deduplicados para evitar registros da mesma oferta.

O diagnóstico pode manter em memória o último texto capturado e eventos da sessão. Ele pode conter nomes e endereços que estiverem visíveis. Pode ser desligado nas configurações; o texto de diagnóstico não é enviado nem gravado em arquivo pelo mecanismo de diagnóstico.

### Capturas e vídeos opcionais

A captura automática para a galeria é desligada por padrão e exige autorização separada. Capturas autorizadas são salvas em `Pictures/CorridaCerta` e podem conter dados visíveis na tela.

A gravação de segurança usa a câmera frontal somente depois de uma ação da pessoa usuária. O áudio é opcional e desligado por padrão. Durante a gravação, o Android mantém seus indicadores de privacidade e o aplicativo mantém uma notificação visível para parar. Vídeos são salvos localmente em `Movies/CorridaCerta` com marca d’água móvel de data e hora.

Arquivos salvos na galeria podem permanecer após a desinstalação e podem ser tratados por aplicativos de galeria, backup ou sincronização conforme as configurações desses serviços. Para removê-los, use a galeria, o gestor de arquivos e o serviço de backup aplicável.

## 3. Compartilhamento e acesso à rede

A versão descrita não transmite conteúdo de cartões de oferta, histórico, diagnósticos, imagens, vídeos, áudio ou configurações para servidores próprios. Ela não contém anúncios, telemetria, análise remota, conta de usuário, faturação ou servidor próprio.

A cópia do diagnóstico depende de toque explícito da pessoa usuária. Imagens e vídeos podem ser compartilhados posteriormente pela pessoa a partir da galeria ou de outros aplicativos, sob as regras desses aplicativos.

## 4. Retenção e exclusão

O histórico e as preferências ficam no armazenamento privado enquanto os dados do aplicativo existirem no aparelho. A opção **Apagar todo o histórico** remove os registros locais. Para remover preferências e outros dados privados, use os controles do Android para limpar os dados do aplicativo ou desinstalá-lo.

O aplicativo desativa o backup automático de seus dados privados. Isso não controla cópias de imagens e vídeos guardados na galeria compartilhada.

## 5. Permissões e controles

O aplicativo pode solicitar ou direcionar para os seguintes controles, conforme a função escolhida:

- **Acessibilidade**, para ler conteúdo visível de cartões em aplicativos compatíveis;
- **Aparecer sobre outros aplicativos**, para exibir o balão e o cartão de análise;
- **Câmera**, para gravação frontal iniciada pela pessoa;
- **Microfone**, somente se a gravação com áudio for escolhida;
- **Notificações**, para informar gravação ativa;
- **Vibração**, para alertas curtos.

A pessoa pode revogar permissões, desligar o leitor, pausar a leitura, desligar a leitura visual e desativar a captura para a galeria. Desativar uma função pode impedir o funcionamento dela, mas não apaga automaticamente arquivos já criados.

## 6. Contato e alterações

**Contato de privacidade e suporte:** [wbsxavier01@gmail.com](mailto:wbsxavier01@gmail.com)

Este e-mail é o canal público de suporte e privacidade do Corrida Certa. Esta política será atualizada se mudarem recursos, permissões, monetização ou fluxo de dados.

## Referências

[1]: https://support.google.com/googleplay/android-developer/answer/10144311?hl=pt-BR "Google Play — Política de Dados do usuário"
[2]: https://support.google.com/googleplay/android-developer/answer/10787469?hl=pt-BR "Google Play — Informações para Segurança dos dados"
[3]: https://developer.android.com/about/versions/14/features/app-metadata "Android Developers — Metadados e definições de coleta de dados"
