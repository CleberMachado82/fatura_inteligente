FATURA INTELIGENTE - PROJETO ANDROID

O que este projeto faz:
- Empacota o HTML enviado em um aplicativo Android (WebView).
- Mantém JavaScript e DOM Storage habilitados para o funcionamento do painel e do localStorage.
- Guarda os dados localmente no armazenamento do WebView deste aplicativo.
- Não usa Supabase nem banco de dados em nuvem.
- Requer internet para carregar Tailwind, Lucide, Chart.js, SheetJS, Google Fonts e o logo Itaú, pois o HTML original usa esses recursos por CDN.

COMO GERAR O APK PELO CELULAR (GitHub):
1. Extraia este ZIP no celular.
2. Entre em github.com e crie um repositório novo, por exemplo: fatura-inteligente.
3. Envie TODOS os arquivos e pastas deste projeto para a raiz do repositório. Inclua a pasta oculta .github/workflows.
4. No repositório, abra a aba Actions.
5. Se aparecer a solicitação, habilite GitHub Actions.
6. Escolha "Gerar APK Android" e toque em "Run workflow".
7. Quando terminar, abra a execução concluída e baixe o artefato "Fatura-Inteligente-APK".
8. Extraia o arquivo baixado; dentro estará app-debug.apk. Abra-o no Android para instalar, autorizando a instalação para o navegador/gerenciador de arquivos quando solicitado.

OBSERVAÇÕES IMPORTANTES:
- O APK ainda não foi compilado; este ZIP contém o projeto-fonte e a automação para compilar.
- A primeira compilação pode levar alguns minutos.
- Os dados salvos no navegador não são importados automaticamente para o APK.
- Desinstalar o aplicativo pode apagar os dados locais. Use a função de backup do painel antes de trocar de aparelho ou desinstalar.
- Como o HTML original carrega bibliotecas por CDN, as funções que dependem delas precisam de internet.
