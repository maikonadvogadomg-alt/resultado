// JavaScript do projeto
console.log("Projeto carregado!");
2026-05-17T18:42:45.2828306Z Versão atual do executor: '2.334.0'
2026-05-17T18:42:45.2852316Z ##[group]Provisionador de Imagem do Runner
2026-05-17T18:42:45.2853129Z Agente de Computação Hospedado
2026-05-17T18:42:45.2853600Z Versão: 20260213.493
2026-05-17T18:42:45.2854154Z Commit: 5c115507f6dd24b8de37d8bbe0bb4509d0cc0fa3
2026-05-17T18:42:45.2854759Z Data de compilação: 2026-02-13T00:28:41Z
2026-05-17T18:42:45.2855377Z ID do trabalhador: {7bf8a0c3-7da0-46b9-beff-97edc987b109}
2026-05-17T18:42:45.2855989Z Região do Azure: westcentralus
2026-05-17T18:42:45.2856541Z ##[endgroup]
2026-05-17T18:42:45.2857817Z ##[grupo]Sistema Operacional
2026-05-17T18:42:45.2858369Z Ubuntu
2026-05-17T18:42:45.2858831Z 24.04.4
2026-05-17T18:42:45.2859234Z LTS
2026-05-17T18:42:45.2859678Z ##[endgroup]
2026-05-17T18:42:45.2860084Z ##[group]Imagem do Corredor
2026-05-17T18:42:45.2860767Z Imagem: ubuntu-24.04
2026-05-17T18:42:45.2861197Z Versão: 20260513.135.3
2026-05-17T18:42:45.2862327Z Software incluído: https://github.com/actions/runner-images/blob/ubuntu24/20260513.135/images/ubuntu/Ubuntu2404-Readme.md
2026-05-17T18:42:45.2863602Z Lançamento da imagem: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260513.135
2026-05-17T18:42:45.2864411Z ##[endgroup]
2026-05-17T18:42:45.2865347Z ##[group]GITHUB_TOKEN Permissões
2026-05-17T18:42:45.2867159Z Conteúdo: ler
2026-05-17T18:42:45.2867693Z Metadados: lidos
2026-05-17T18:42:45.2868169Z Pacotes: ler
2026-05-17T18:42:45.2868587Z ##[endgroup]
2026-05-17T18:42:45.2870862Z Fonte secreta: Ações
2026-05-17T18:42:45.2871505Z Preparar diretório de fluxo de trabalho
2026-05-17T18:42:45.3197636Z Prepare todas as ações necessárias
2026-05-17T18:42:45.3235609Z Obtendo informações de download da ação
2026-05-17T18:42:45.7815036Z Baixar repositório de ações 'actions/checkout@v4' (SHA:34e114876b0b11c390a56381ad16ebd13914f8d5)
2026-05-17T18:42:45.9399937Z Baixar repositório de ações 'actions/setup-java@v4' (SHA:c1e323688fd81a25caa38c78aa6df2d33d3e20d9)
2026-05-17T18:42:46.8602059Z Baixar repositório de ações 'gradle/actions@v3' (SHA:d9c87d481d55275bb5441eef3fe0e46805f9ef70)
2026-05-17T18:42:48.0231759Z Baixar repositório de ações 'android-actions/setup-android@v3' (SHA:9fc6c4e9069bf8d3d10b2204b1fb8f6ef7065407)
2026-05-17T18:42:48.4543147Z Baixar repositório de ações 'actions/setup-node@v4' (SHA:49933ea5288caeca8642d1e84afbd3f7d6820020)
2026-05-17T18:42:48.5243107Z Baixar repositório de ações 'actions/upload-artifact@v4' (SHA:ea165f8d65b6e75b540449e92b4886f43607fa02)
2026-05-17T18:42:48.7315488Z Nome completo da tarefa: build
2026-05-17T18:42:48.7908367Z ##[group]Executar ações/checkout@v4
2026-05-17T18:42:48.7908895Z com:
2026-05-17T18:42:48.7909206Z repositório: maikonadvogadomg-alt/sk-code-editor-v4-web-1-android-android
2026-05-17T18:42:48.7909786Z token: ***
2026-05-17T18:42:48.7909964Z ssh-strict: true
2026-05-17T18:42:48.7910157Z ssh-user: git
2026-05-17T18:42:48.7910505Z persist-credentials: true
2026-05-17T18:42:48.7910729Z limpo: verdadeiro
2026-05-17T18:42:48.7910938Z sparse-checkout-cone-mode: true
2026-05-17T18:42:48.7911159Z profundidade de busca: 1
2026-05-17T18:42:48.7911341Z fetch-tags: false
2026-05-17T18:42:48.7911544Z mostrar-progresso: verdadeiro
2026-05-17T18:42:48.7911731Z lfs: falso
2026-05-17T18:42:48.7911890Z submódulos: falso
2026-05-17T18:42:48.7912073Z definir-diretório-seguro: verdadeiro
2026-05-17T18:42:48.7912476Z ##[endgroup]
2026-05-17T18:42:48.8955643Z Sincronizando repositório: maikonadvogadomg-alt/sk-code-editor-v4-web-1-android-android
2026-05-17T18:42:48.8957184Z ##[group]Obtendo informações da versão do Git
2026-05-17T18:42:48.8957902Z O diretório de trabalho é '/home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android'
2026-05-17T18:42:48.8958631Z [comando]/usr/bin/git versão
2026-05-17T18:42:48.9003213Z versão do git 2.54.0
17-05-2026T18:42:48.9026263Z ##[grupo final]
2026-05-17T18:42:48.9040319Z Substituindo temporariamente HOME='/home/runner/work/_temp/e0c0015b-ed14-47d2-baac-2afd4533f4fd' antes de fazer alterações globais na configuração do git
2026-05-17T18:42:48.9042087Z Adicionando o diretório do repositório à configuração global temporária do Git como um diretório seguro.
2026-05-17T18:42:48.9055521Z [comando]/usr/bin/git config --global --add safe.directory /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android
2026-05-17T18:42:48.9094999Z Excluindo o conteúdo de '/home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android'
2026-05-17T18:42:48.9098122Z ##[group]Inicializando o repositório
2026-05-17T18:42:48.9103477Z [comando]/usr/bin/git init /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android
2026-05-17T18:42:48.9176761Z dica: Usando 'master' como nome para a branch inicial. Este é o nome de branch padrão.
2026-05-17T18:42:48.9177621Z dica: mudará para "main" no Git 3.0. Para configurar o nome da branch inicial.
2026-05-17T18:42:48.9178088Z dica: para usar em todos os seus novos repositórios, o que suprimirá este aviso.
2026-05-17T18:42:48.9178418Z dica: chamada:
2026-05-17T18:42:48.9178594Z dica:
2026-05-17T18:42:48.9178854Z dica: git config --global init.defaultBranch <nome>
2026-05-17T18:42:48.9179175Z dica:
2026-05-17T18:42:48.9179582Z dica: Nomes comumente escolhidos em vez de 'master' são 'main', 'trunk' e
2026-05-17T18:42:48.9180306Z dica: 'desenvolvimento'. O branch recém-criado pode ser renomeado através deste comando:
2026-05-17T18:42:48.9181049Z dica:
2026-05-17T18:42:48.9181342Z dica: git branch -m <nome>
2026-05-17T18:42:48.9181677Z dica:
2026-05-17T18:42:48.9182182Z dica: Desative esta mensagem com "git config set advice.defaultBranchName false"
2026-05-17T18:42:48.9183420Z Inicializado repositório Git vazio em /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android/.git/
2026-05-17T18:42:48.9191308Z [comando]/usr/bin/git remote add origin https://github.com/maikonadvogadomg-alt/sk-code-editor-v4-web-1-android-android
2026-05-17T18:42:48.9223345Z ##[endgroup]
2026-05-17T18:42:48.9223978Z ##[group]Desativando a coleta automática de lixo
2026-05-17T18:42:48.9228273Z [comando]/usr/bin/git config --local gc.auto 0
2026-05-17T18:42:48.9250651Z ##[endgroup]
2026-05-17T18:42:48.9251239Z ##[group]Configurando a autenticação
2026-05-17T18:42:48.9257986Z [comando]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-05-17T18:42:48.9285814Z [comando]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-05-17T18:42:48.9553865Z [comando]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-05-17T18:42:48.9579752Z [comando]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-05-17T18:42:48.9749776Z [comando]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-05-17T18:42:48.9774621Z [comando]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-05-17T18:42:48.9952861Z [comando]/usr/bin/git config --local http.https://github.com/.extraheader AUTORIZAÇÃO: básica ***
2026-05-17T18:42:48.9981008Z ##[endgroup]
2026-05-17T18:42:48.9981553Z ##[group]Obtendo o repositório
2026-05-17T18:42:48.9988901Z [comando]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +27f1ece1b43ecb530dc262cb14bbb9d278eaa267:refs/remotes/origin/main
2026-05-17T18:42:49.6831236Z De https://github.com/maikonadvogadomg-alt/sk-code-editor-v4-web-1-android-android
2026-05-17T18:42:49.6831931Z * [nova ref] 27f1ece1b43ecb530dc262cb14bbb9d278eaa267 -> origem/principal
2026-05-17T18:42:49.6861101Z ##[endgroup]
2026-05-17T18:42:49.6861685Z ##[group]Determinando as informações de finalização da compra
2026-05-17T18:42:49.6864068Z ##[endgroup]
2026-05-17T18:42:49.6869165Z [comando]/usr/bin/git sparse-checkout disable
2026-05-17T18:42:49.6903481Z [comando]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-05-17T18:42:49.6923516Z ##[group]Verificando a referência
2026-05-17T18:42:49.6928139Z [comando]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2026-05-17T18:42:49.7165123Z Mudou para uma nova ramificação 'principal'
2026-05-17T18:42:49.7166896Z branch 'main' set up to track 'origin/main'.
2026-05-17T18:42:49.7171766Z ##[endgroup]
2026-05-17T18:42:49.7205320Z [comando]/usr/bin/git log -1 --format=%H
2026-05-17T18:42:49.7226133Z 27f1ece1b43ecb530dc262cb14bbb9d278eaa267
2026-05-17T18:42:49.7444414Z ##[group]Executar ações/setup-java@v4
2026-05-17T18:42:49.7444674Z com:
2026-05-17T18:42:49.7444841Z java-version: 17
2026-05-17T18:42:49.7445029Z distribuição: temurin
2026-05-17T18:42:49.7445229Z pacote java: jdk
2026-05-17T18:42:49.7445424Z check-latest: false
2026-05-17T18:42:49.7445614Z server-id: github
2026-05-17T18:42:49.7445796Z nome de usuário do servidor: GITHUB_ACTOR
2026-05-17T18:42:49.7446030Z senha-do-servidor: GITHUB_TOKEN
2026-05-17T18:42:49.7446241Z sobrescrever configurações: verdadeiro
2026-05-17T18:42:49.7446451Z status do trabalho: sucesso
2026-05-17T18:42:49.7446794Z token: ***
2026-05-17T18:42:49.7446967Z ##[endgroup]
2026-05-17T18:42:49.9381173Z ##[grupo]Distribuições instaladas
2026-05-17T18:42:49.9550248Z Java 17.0.19+10 resolvido do cache de ferramentas
2026-05-17T18:42:49.9550971Z Definindo Java 17.0.19+10 como padrão
2026-05-17T18:42:49.9563416Z Criando toolchains.xml para a versão 17 do JDK a partir de temurin
2026-05-17T18:42:49.9633381Z Escrevendo em /home/runner/.m2/toolchains.xml
2026-05-17T18:42:49.9633933Z
2026-05-17T18:42:49.9634572Z Configuração Java:
2026-05-17T18:42:49.9635310Z Distribuição: temurin
2026-05-17T18:42:49.9635682Z Versão: 17.0.19+10
2026-05-17T18:42:49.9636190Z Caminho: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:42:49.9636640Z
17/05/2026T18:42:49.9637159Z ##[grupo final]
2026-05-17T18:42:49.9652316Z Criando settings.xml com o ID do servidor: github
2026-05-17T18:42:49.9656626Z Escrevendo em /home/runner/.m2/settings.xml
2026-05-17T18:42:49.9859146Z ##[group]Executar gradle/actions/setup-gradle@v3
2026-05-17T18:42:49.9859527Z com:
2026-05-17T18:42:49.9859729Z versão do Gradle: 8.6
2026-05-17T18:42:49.9860073Z cache-desativado: falso
2026-05-17T18:42:49.9860314Z cache-read-only: false
2026-05-17T18:42:49.9860737Z cache-write-only: false
2026-05-17T18:42:49.9861034Z cache-overwrite-existing: false
2026-05-17T18:42:49.9861395Z gradle-home-cache-includes: caches
notificações

2026-05-17T18:42:49.9861768Z gradle-home-cache-cleanup: false
2026-05-17T18:42:49.9862097Z add-job-summary: always
2026-05-17T18:42:49.9862401Z adicionar-resumo-de-trabalho-como-comentário-de-pr: nunca
2026-05-17T18:42:49.9862698Z gráfico de dependência: desativado
2026-05-17T18:42:49.9863034Z dependency-graph-continue-on-failure: true
2026-05-17T18:42:49.9863336Z build-scan-publish: false
2026-05-17T18:42:49.9863626Z validate-wrappers: false
2026-05-17T18:42:49.9863951Z generate-job-summary: true
2026-05-17T18:42:49.9864222Z gradle-home-cache-strict-match: false
2026-05-17T18:42:49.9864610Z workflow-job-context: null
2026-05-17T18:42:49.9865107Z github-token: ***
2026-05-17T18:42:49.9865360Z env:
2026-05-17T18:42:49.9865652Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:42:49.9866229Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:42:49.9866609Z ##[endgroup]
2026-05-17T18:42:53.2667623Z Locais padrão do JDK mesclados em /home/runner/.m2/toolchains.xml
2026-05-17T18:42:53.2670031Z ##[group]Restaurar estado do Gradle a partir do cache
2026-05-17T18:42:53.3863130Z ##[aviso]Falha ao restaurar gradle-home-v1|Linux|build[e080f0fdc288b6f0c5023fd4b86f7a10]-27f1ece1b43ecb530dc262cb14bbb9d278eaa267: Erro: O serviço de cache respondeu com 400
2026-05-17T18:42:53.3927730Z O cache do diretório inicial do usuário do Gradle não foi encontrado. Será inicializado vazio.
2026-05-17T18:42:53.3928855Z ##[endgroup]
2026-05-17T18:42:53.5929511Z ##[group]Provisionar Gradle 8.6
2026-05-17T18:42:53.6576227Z ##[aviso]Falha ao restaurar a distribuição Gradle 8.6: Erro: O serviço de cache respondeu com 400
2026-05-17T18:42:53.6578968Z A distribuição Gradle 8.6 não foi encontrada no cache. Será feita a instalação.
2026-05-17T18:42:54.7540306Z Baixado https://services.gradle.org/distributions/gradle-8.6-bin.zip para /home/runner/gradle-installations/downloads/gradle-8.6-bin.zip (tamanho 132788867)
2026-05-17T18:42:54.7787196Z [comando]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android --files-from manifest.txt --use-compress-program zstdmt
2026-05-17T18:42:54.9625474Z ##[aviso]Falha ao salvar a distribuição Gradle 8.6: Erro: <h2>Nossos serviços não estão disponíveis no momento</h2><p>Estamos trabalhando para restaurar todos os serviços o mais rápido possível. Volte em breve.</p>0LgwKagAAAAAUxIARCSAnRoX/zj8L2t0EU0xDMzFFREdFMDExOQBFZGdl
2026-05-17T18:42:54.9642196Z [comando]/usr/bin/unzip -o -q /home/runner/gradle-installations/downloads/gradle-8.6-bin.zip
2026-05-17T18:42:55.9372429Z Gradle 8.6 extraído para /home/runner/gradle-installations/installs/gradle-8.6
2026-05-17T18:42:55.9374115Z Executável do Gradle provisionado em /home/runner/gradle-installations/installs/gradle-8.6/bin/gradle
2026-05-17T18:42:55.9375708Z ##[endgroup]
2026-05-17T18:42:55.9505788Z ##[group]Executar android-actions/setup-android@v3
2026-05-17T18:42:55.9506102Z com:
2026-05-17T18:42:55.9506433Z cmdline-tools-version: 12266719
2026-05-17T18:42:55.9506725Z aceitar-licenças-do-sdk-android: true
2026-05-17T18:42:55.9507069Z log-accepted-android-sdk-licenses: true
2026-05-17T18:42:55.9507442Z pacotes: ferramentas ferramentas-de-plataforma
2026-05-17T18:42:55.9507699Z env:
2026-05-17T18:42:55.9508053Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:42:55.9508589Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:42:55.9509038Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:42:55.9509358Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:42:55.9509717Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:42:55.9510184Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:42:55.9511118Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:42:55.9511477Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:42:55.9511822Z ##[endgroup]
2026-05-17T18:42:56.0574728Z Encontrado o sdkmanager pré-instalado em /usr/local/lib/android/sdk/cmdline-tools/latest com o seguinte arquivo source.properties:
2026-05-17T18:42:56.0575646Z Pkg.Revision=12.0
2026-05-17T18:42:56.0576014Z Pkg.Path=cmdline-tools;12.0
2026-05-17T18:42:56.0576407Z Pkg.Desc=Ferramentas de linha de comando do SDK do Android
2026-05-17T18:42:56.0576794Z
2026-05-17T18:42:56.0576993Z Versão incorreta no sdkmanager pré-instalado
2026-05-17T18:42:56.0577788Z Baixando ferramentas de linha de comando de https://dl.google.com/android/repository/commandlinetools-linux-12266719_latest.zip
2026-05-17T18:42:56.8435315Z [comando]/usr/bin/unzip -o -q /home/runner/work/_temp/7a6b4fe7-8875-42f2-82f2-b104d4ff4827
2026-05-17T18:42:57.6432558Z Aceitando licenças do SDK do Android
2026-05-17T18:42:57.6438530Z [comando]/usr/local/lib/android/sdk/cmdline-tools/16.0/bin/sdkmanager --licenses
2026-05-17T18:43:02.1338118Z Carregando repositório local...                                                     
2026-05-17T18:43:02.1338853Z [========= ] 25% Carregando repositório local...       
2026-05-17T18:43:04.1531373Z [========= ] 25% Buscando repositório remoto...        
2026-05-17T18:43:04.5173595Z [========== ] 26% Buscando repositório remoto...        
2026-05-17T18:43:04.5177494Z [============ ] 31% Buscando repositório remoto...        
2026-05-17T18:43:04.5465865Z [============ ] 32% Buscando repositório remoto...        
2026-05-17T18:43:04.5478628Z [============= ] 33% Buscando repositório remoto...        
2026-05-17T18:43:04.5772439Z [============= ] 35% Buscando repositório remoto...        
2026-05-17T18:43:04.5773722Z [============== ] 36% Buscando repositório remoto...        
2026-05-17T18:43:04.6043107Z [============== ] 37% Buscando repositório remoto...        
2026-05-17T18:43:04.6071302Z [=============== ] 38% Buscando repositório remoto...        
2026-05-17T18:43:04.6263117Z [=============== ] 39% Buscando repositório remoto...        
2026-05-17T18:43:04.6271740Z [================ ] 40% Buscando repositório remoto...        
2026-05-17T18:43:04.6453275Z [================ ] 41% Buscando repositório remoto...        
2026-05-17T18:43:04.6469208Z [================ ] 42% Buscando repositório remoto...        
2026-05-17T18:43:04.6684023Z [================= ] 44% Buscando repositório remoto...        
2026-05-17T18:43:04.6685088Z [================= ] 45% Buscando repositório remoto...        
2026-05-17T18:43:04.6905623Z [================== ] 46% Buscando repositório remoto...        
2026-05-17T18:43:04.6907306Z [================== ] 47% Buscando repositório remoto...        
2026-05-17T18:43:04.7076721Z [=================== ] 48% Buscando repositório remoto...        
2026-05-17T18:43:04.7077712Z [=================== ] 49% Buscando repositório remoto...        
2026-05-17T18:43:04.7253908Z [==================== ] 50% Buscando repositório remoto...        
2026-05-17T18:43:04.7255053Z [==================== ] 51% Buscando repositório remoto...        
2026-05-17T18:43:04.7559735Z [==================== ] 53% Buscando repositório remoto...        
2026-05-17T18:43:04.7564068Z [===================== ] 54% Buscando repositório remoto...        
2026-05-17T18:43:04.7788860Z [===================== ] 55% Buscando repositório remoto...        
2026-05-17T18:43:04.7789984Z [====================== ] 56% Buscando repositório remoto...        
2026-05-17T18:43:04.8137195Z [====================== ] 57% Buscando repositório remoto...        
2026-05-17T18:43:04.8138392Z [======================= ] 58% Buscando repositório remoto...        
2026-05-17T18:43:04.8232658Z [======================= ] 59% Buscando repositório remoto...        
2026-05-17T18:43:04.8236371Z [======================== ] 60% Buscando repositório remoto...        
2026-05-17T18:43:04.8435603Z [======================== ] 61% Buscando repositório remoto...        
2026-05-17T18:43:04.8437255Z [========================= ] 63% Buscando repositório remoto...        
2026-05-17T18:43:04.8640612Z [========================= ] 64% Buscando repositório remoto...        
2026-05-17T18:43:04.8641796Z [========================= ] 65% Buscando repositório remoto...        
2026-05-17T18:43:04.9000237Z [========================== ] 66% Buscando repositório remoto...        
2026-05-17T18:43:04.9037142Z [========================== ] 67% Buscando repositório remoto...        
2026-05-17T18:43:04.9366466Z [=========================== ] 68% Buscando repositório remoto...        
2026-05-17T18:43:04.9367554Z [=========================== ] 69% Buscando repositório remoto...        
2026-05-17T18:43:05.0161821Z [============================ ] 70% Buscando repositório remoto...        
2026-05-17T18:43:05.0168772Z [============================ ] 72% Buscando repositório remoto...        
2026-05-17T18:43:05.0797470Z [============================= ] 73% Buscando repositório remoto...        
2026-05-17T18:43:05.0808822Z [============================= ] 74% Buscando repositório remoto...        
2026-05-17T18:43:05.0873777Z [============================= ] 75% Buscando repositório remoto...        
2026-05-17T18:43:05.1002724Z [============================= ] 75% Calculando atualizações...              
2026-05-17T18:43:05.1003531Z [=======================================] 100% Atualizações de computação...             
2026-05-17T18:43:05.1426961Z 6 de 7 Licenças de pacote SDK não aceitas.
2026-05-17T18:43:05.1429032Z Analisar as licenças que não foram aceitas (s/N)?
2026-05-17T18:43:05.1429862Z 1/6: Licença android-googletv-license:
2026-05-17T18:43:05.1430554Z ---------------------------------------
2026-05-17T18:43:05.1434904Z Termos e Condições
2026-05-17T18:43:05.1437499Z
2026-05-17T18:43:05.1438144Z Este é o Contrato de Licença do Complemento do Google TV para o Kit de Desenvolvimento de Software Android.
2026-05-17T18:43:05.1438810Z
2026-05-17T18:43:05.1439055Z 1. Introdução
2026-05-17T18:43:05.1439352Z
2026-05-17T18:43:05.1441982Z 1.1 O complemento Google TV para o Kit de Desenvolvimento de Software Android (referido neste Contrato de Licença como "Complemento Google TV" e incluindo especificamente os arquivos do sistema Android, APIs empacotadas e complementos de APIs do Google) é licenciado para você sujeito aos termos deste Contrato de Licença. Este Contrato de Licença constitui um contrato juridicamente vinculativo entre você e o Google em relação ao seu uso do complemento Google TV.
2026-05-17T18:43:05.1444765Z
2026-05-17T18:43:05.1446260Z 1.2 "Google" significa Google Inc., uma corporação de Delaware com sede principal em 1600 Amphitheatre Parkway, Mountain View, CA 94043, Estados Unidos.
2026-05-17T18:43:05.1447464Z
2026-05-17T18:43:05.1447749Z 2. Aceitação deste Contrato de Licença
2026-05-17T18:43:05.1448134Z
2026-05-17T18:43:05.1449021Z 2.1 Para usar o complemento Google TV, você precisa primeiro concordar com este Contrato de Licença. Você não poderá usar o complemento Google TV se não aceitar este Contrato de Licença.
2026-05-17T18:43:05.1450089Z
2026-05-17T18:43:05.1450531Z 2.2 Você pode aceitar este Contrato de Licença por:
2026-05-17T18:43:05.1450982Z
2026-05-17T18:43:05.1451548Z (A) clicando para aceitar ou concordar com este Contrato de Licença, quando esta opção estiver disponível para você; ou
2026-05-17T18:43:05.1452311Z
2026-05-17T18:43:05.1453266Z (B) ao usar efetivamente o complemento do Google TV. Nesse caso, você concorda que o uso do complemento do Google TV constitui aceitação do Contrato de Licença a partir desse momento.
2026-05-17T18:43:05.1454396Z
2026-05-17T18:43:05.1456039Z 2.3 Você não poderá usar o complemento Google TV nem aceitar o Contrato de Licença se for uma pessoa impedida de receber o complemento Google TV pelas leis dos Estados Unidos ou de outros países, incluindo o país em que reside ou de onde usa o complemento Google TV.
2026-05-17T18:43:05.1457838Z
2026-05-17T18:43:05.1460005Z 2.4 Se você concordar em se vincular a este Contrato de Licença em nome de seu empregador ou outra entidade, você declara e garante que possui plena autoridade legal para vincular seu empregador ou tal entidade a este Contrato de Licença. Caso não possua a autoridade necessária, você não poderá aceitar o Contrato de Licença nem usar o complemento do Google TV em nome de seu empregador ou outra entidade.
2026-05-17T18:43:05.1462538Z
2026-05-17T18:43:05.1462834Z 3. Licença do complemento Google TV do Google
2026-05-17T18:43:05.1463263Z
2026-05-17T18:43:05.1464688Z 3.1 Sujeito aos termos deste Contrato de Licença, o Google concede a você uma licença limitada, mundial, isenta de royalties, não transferível e não exclusiva para usar o complemento do Google TV exclusivamente para desenvolver aplicativos para serem executados na plataforma Google TV.
2026-05-17T18:43:05.1466261Z
2026-05-17T18:43:05.1468658Z 3.2 Você concorda que o Google ou terceiros detêm todos os direitos legais, títulos e interesses relativos ao complemento do Google TV, incluindo quaisquer Direitos de Propriedade Intelectual que subsistam no complemento do Google TV. "Direitos de Propriedade Intelectual" significa todos e quaisquer direitos sob a lei de patentes, lei de direitos autorais, lei de segredos comerciais, lei de marcas registradas e quaisquer outros direitos de propriedade. O Google reserva-se todos os direitos não expressamente concedidos a você.
2026-05-17T18:43:05.1471574Z
2026-05-17T18:43:05.1475315Z 3.3 Exceto na medida exigida pelas licenças de terceiros aplicáveis, você não pode copiar (exceto para fins de backup), modificar, adaptar, redistribuir, descompilar, fazer engenharia reversa, desmontar ou criar trabalhos derivados do Complemento do Google TV ou de qualquer parte dele. Exceto na medida exigida pelas licenças de terceiros aplicáveis, você não pode carregar nenhuma parte do Complemento do Google TV em um celular, televisão ou qualquer outro dispositivo de hardware, exceto um computador pessoal, combinar qualquer parte do Complemento do Google TV com outro software ou distribuir qualquer software ou dispositivo que incorpore uma parte do Complemento do Google TV.
2026-05-17T18:43:05.1479493Z
2026-05-17T18:43:05.1481042Z 3.4 O uso, a reprodução e a distribuição de componentes do complemento do Google TV licenciados sob uma licença de software de código aberto são regidos exclusivamente pelos termos dessa licença de software de código aberto e não por este Contrato de Licença.
2026-05-17T18:43:05.1482670Z
2026-05-17T18:43:05.1485769Z 3.5 Você concorda que a forma e a natureza do complemento do Google TV fornecido pelo Google podem mudar sem aviso prévio e que versões futuras do complemento do Google TV podem ser incompatíveis com aplicativos desenvolvidos em versões anteriores do complemento do Google TV. Você concorda que o Google pode interromper (permanentemente ou temporariamente) o fornecimento do complemento do Google TV (ou quaisquer recursos dentro do complemento do Google TV) para você ou para os usuários em geral, a critério exclusivo do Google, sem aviso prévio.
2026-05-17T18:43:05.1488854Z
2026-05-17T18:43:05.1491118Z 3.6 Nada neste Contrato de Licença lhe dá o direito de usar quaisquer nomes comerciais, marcas registradas, marcas de serviço, logotipos, nomes de domínio ou outras características distintivas da marca do Google ou de seus licenciadores.
2026-05-17T18:43:05.1492759Z
2026-05-17T18:43:05.1493980Z 3.7 Você concorda em não remover, ocultar ou alterar quaisquer avisos de direitos de propriedade (incluindo avisos de direitos autorais e marcas registradas) que possam estar afixados ou contidos no complemento do Google TV.
2026-05-17T18:43:05.1495372Z
2026-05-17T18:43:05.1495663Z 4. Uso do complemento Google TV por você
2026-05-17T18:43:05.1496078Z
2026-05-17T18:43:05.1497768Z 4.1 O Google concorda que não obtém nenhum direito, título ou interesse seu (ou de seus licenciadores) sob este Contrato de Licença em relação a quaisquer aplicativos de software que você desenvolva usando o complemento do Google TV, incluindo quaisquer direitos de propriedade intelectual que existam nesses aplicativos.
2026-05-17T18:43:05.1499589Z
2026-05-17T18:43:05.1501879Z 4.2 Você concorda em usar o complemento do Google TV e escrever aplicativos apenas para fins permitidos por (a) este Contrato de Licença e (b) qualquer lei, regulamento ou práticas ou diretrizes geralmente aceitas aplicáveis ​​nas jurisdições relevantes (incluindo quaisquer leis relativas à exportação de dados ou software de e para os Estados Unidos ou outros países relevantes).
2026-05-17T18:43:05.1504305Z
2026-05-17T18:43:05.1509167Z 4.3 Você concorda que, se usar o complemento do Google TV para desenvolver aplicativos para usuários do público em geral, protegerá a privacidade e os direitos legais desses usuários. Se os usuários fornecerem nomes de usuário, senhas ou outras informações de login ou informações pessoais, você deverá informá-los de que essas informações estarão disponíveis para o seu aplicativo e deverá fornecer um aviso de privacidade e proteção legalmente adequados para esses usuários. Se o seu aplicativo armazenar informações pessoais ou confidenciais fornecidas pelos usuários, deverá fazê-lo de forma segura. Se o usuário fornecer ao seu aplicativo informações da Conta do Google, seu aplicativo poderá usar essas informações somente para acessar a Conta do Google do usuário quando e para os fins limitados para os quais o usuário lhe tiver dado permissão explícita para fazê-lo.
2026-05-17T18:43:05.1514334Z
2026-05-17T18:43:05.1516757Z 4.4 Você concorda que não se envolverá em nenhuma atividade com o complemento do Google TV, incluindo o desenvolvimento ou distribuição de um aplicativo, que interfira, interrompa, danifique ou acesse de forma não autorizada os servidores, redes ou outras propriedades ou serviços de terceiros, incluindo, entre outros, o Google, distribuidores de programas de vídeo multicanal ou qualquer operadora de comunicações móveis.
2026-05-17T18:43:05.1519496Z
2026-05-17T18:43:05.1521888Z 4.5 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) quaisquer dados, conteúdo ou recursos que você criar, transmitir ou exibir através da plataforma Google TV e/ou aplicativos para a plataforma Google TV, e pelas consequências de suas ações (incluindo qualquer perda ou dano que o Google possa sofrer) ao fazê-lo.
2026-05-17T18:43:05.1524550Z
2026-05-17T18:43:05.1526924Z 4.6 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) qualquer violação de suas obrigações sob este Contrato de Licença, qualquer contrato de terceiros aplicável ou Termos de Serviço, ou qualquer lei ou regulamento aplicável, e pelas consequências (incluindo qualquer perda ou dano que o Google ou terceiros possam sofrer) de tal violação.
2026-05-17T18:43:05.1529488Z
2026-05-17T18:43:05.1529774Z 5. Suas credenciais de desenvolvedor
2026-05-17T18:43:05.1530154Z
2026-05-17T18:43:05.1532215Z 5.1 Você concorda que é responsável por manter a confidencialidade de quaisquer credenciais de desenvolvedor que possam ser emitidas para você pelo Google ou que você possa escolher, e que será o único responsável por todos os aplicativos desenvolvidos com suas credenciais de desenvolvedor.
2026-05-17T18:43:05.1534179Z
2026-05-17T18:43:05.1534460Z 6. Privacidade e Informações
2026-05-17T18:43:05.1534815Z
2026-05-17T18:43:05.1537673Z 6.1 Para inovar e aprimorar continuamente o complemento do Google TV, o Google poderá coletar determinadas estatísticas de uso do software, incluindo, entre outras, um identificador exclusivo, o endereço IP associado, o número da versão do software e informações sobre quais ferramentas e/ou serviços do complemento do Google TV estão sendo usados ​​e como estão sendo usados. Antes que qualquer uma dessas informações seja coletada, o complemento do Google TV notificará você e solicitará seu consentimento. Caso você negue o consentimento, as informações não serão coletadas.
2026-05-17T18:43:05.1540949Z
2026-05-17T18:43:05.1541750Z 6.2 Os dados coletados são examinados de forma agregada para melhorar o complemento do Google TV e são mantidos de acordo com a Política de Privacidade do Google.
2026-05-17T18:43:05.1542776Z
2026-05-17T18:43:05.1543122Z 7. Aplicativos de terceiros para a plataforma Google TV
2026-05-17T18:43:05.1543636Z
2026-05-17T18:43:05.1547146Z 7.1 Se você usar o complemento do Google TV para executar aplicativos desenvolvidos por terceiros ou que acessem dados, conteúdo ou recursos fornecidos por terceiros, você concorda que o Google não é responsável por esses aplicativos, dados, conteúdo ou recursos. Você entende que todos os dados, conteúdo ou recursos aos quais você possa acessar por meio desses aplicativos de terceiros são de responsabilidade exclusiva da pessoa que os originou e que o Google não é responsável por qualquer perda ou dano que você possa sofrer como resultado do uso ou acesso a quaisquer desses aplicativos, dados, conteúdo ou recursos de terceiros.
2026-05-17T18:43:05.1550988Z
2026-05-17T18:43:05.1553795Z 7.2 Você deve estar ciente de que os dados, o conteúdo e os recursos apresentados a você por meio de um aplicativo de terceiros podem estar protegidos por direitos de propriedade intelectual pertencentes aos provedores (ou a outras pessoas ou empresas em seu nome). Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados, conteúdo ou recursos (no todo ou em parte), a menos que tenha recebido permissão expressa dos respectivos proprietários.
2026-05-17T18:43:05.1556868Z
2026-05-17T18:43:05.1558537Z 7.3 Você reconhece que o uso de aplicativos, dados, conteúdo ou recursos de terceiros pode estar sujeito a termos separados entre você e o respectivo terceiro. Nesse caso, este Contrato de Licença não afeta sua relação jurídica com esses terceiros.
2026-05-17T18:43:05.1560476Z
2026-05-17T18:43:05.1560741Z 8. Usando as APIs do Google TV
2026-05-17T18:43:05.1561148Z
2026-05-17T18:43:05.1565625Z 8.1 Se você usar qualquer API do Google TV para obter dados do Google, você reconhece que os dados ("Conteúdo da API do Google TV") podem ser protegidos por direitos de propriedade intelectual pertencentes ao Google ou às partes que fornecem os dados (ou a outras pessoas ou empresas em nome delas). O uso de qualquer API desse tipo pode estar sujeito a Termos de Serviço adicionais. Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados (no todo ou em parte), a menos que seja permitido pelos Termos de Serviço relevantes. Algumas partes do Conteúdo da API do Google TV são licenciadas ao Google por terceiros, incluindo, entre outros, a Tribune Media Services.
2026-05-17T18:43:05.1569797Z
2026-05-17T18:43:05.1571647Z 8.2 Se você usar qualquer API para recuperar dados de um usuário do Google, você reconhece e concorda que só poderá recuperar os dados com o consentimento explícito do usuário e somente quando, e para os fins limitados para os quais, o usuário lhe deu permissão para fazê-lo.
2026-05-17T18:43:05.1573400Z
2026-05-17T18:43:05.1573983Z 8.3 Exceto conforme explicitamente permitido na Seção 3 (Licença de complemento do Google TV do Google), você deve:
2026-05-17T18:43:05.1574731Z
2026-05-17T18:43:05.1575742Z (a) não modificar nem formatar o Conteúdo da API do Google TV, exceto na medida em que seja razoavelmente e tecnicamente necessário para otimizar a exibição desse Conteúdo da API do Google TV em seu aplicativo;
2026-05-17T18:43:05.1576940Z
2026-05-17T18:43:05.1578274Z (b) não editar o Conteúdo da API do Google TV de forma que o torne impreciso ou altere seu significado inerente (desde que a exibição de trechos não viole o disposto anteriormente); ou
2026-05-17T18:43:05.1579612Z
2026-05-17T18:43:05.1580207Z (c) não criar nenhuma ferramenta ou serviço comercial de medição de audiência usando o conteúdo da API do Google TV
2026-05-17T18:43:05.1581075Z
2026-05-17T18:43:05.1581349Z 9. Rescisão deste Contrato de Licença
2026-05-17T18:43:05.1581753Z
2026-05-17T18:43:05.1582373Z 9.1 Este Contrato de Licença continuará em vigor até ser rescindido por você ou pelo Google, conforme estabelecido abaixo.
2026-05-17T18:43:05.1583168Z
2026-05-17T18:43:05.1584021Z 9.2 Se desejar rescindir este Contrato de Licença, poderá fazê-lo cessando a utilização do complemento Google TV e quaisquer credenciais de desenvolvedor relevantes.
2026-05-17T18:43:05.1584995Z
2026-05-17T18:43:05.1585423Z 9.3 O Google poderá, a qualquer momento, rescindir este Contrato de Licença com você se:
2026-05-17T18:43:05.1585988Z
2026-05-17T18:43:05.1586375Z (A) você violou qualquer disposição deste Contrato de Licença; ou
2026-05-17T18:43:05.1586910Z
2026-05-17T18:43:05.1587177Z (B) O Google é obrigado a fazê-lo por lei; ou
2026-05-17T18:43:05.1587592Z
2026-05-17T18:43:05.1588762Z (C) o parceiro com quem o Google ofereceu a você determinadas partes do complemento do Google TV (como APIs) encerrou seu relacionamento com o Google ou deixou de oferecer a você determinadas partes do complemento do Google TV; ou
2026-05-17T18:43:05.1590094Z
2026-05-17T18:43:05.1592156Z (D) O Google decide não fornecer mais o complemento do Google TV ou determinadas partes do complemento do Google TV para usuários no país em que você reside ou de onde você usa o serviço, ou o fornecimento do complemento do Google TV ou de determinados serviços do complemento do Google TV para você pelo Google, a critério exclusivo do Google, não é mais comercialmente viável.
2026-05-17T18:43:05.1594245Z
2026-05-17T18:43:05.1596867Z 9.4 Quando este Contrato de Licença chegar ao fim, todos os direitos, obrigações e responsabilidades legais que você e o Google tenham adquirido, estejam sujeitos (ou que tenham se acumulado ao longo do tempo enquanto este Contrato de Licença esteve em vigor) ou que estejam expressamente previstos para continuar indefinidamente, não serão afetados por esta rescisão, e as disposições do parágrafo 14.7 continuarão a se aplicar a tais direitos, obrigações e responsabilidades indefinidamente.
2026-05-17T18:43:05.1599707Z
2026-05-17T18:43:05.1599981Z 10. ISENÇÃO DE GARANTIAS
2026-05-17T18:43:05.1600487Z
2026-05-17T18:43:05.1601837Z 10.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O USO DO COMPLEMENTO GOOGLE TV É POR SUA CONTA E RISCO E QUE O COMPLEMENTO GOOGLE TV É FORNECIDO "NO ESTADO EM QUE SE ENCONTRA" E "CONFORME DISPONÍVEL", SEM QUALQUER GARANTIA DO GOOGLE.
2026-05-17T18:43:05.1603209Z
2026-05-17T18:43:05.1604855Z 10.2 O USO DO COMPLEMENTO GOOGLE TV E DE QUALQUER MATERIAL BAIXADO OU OBTIDO DE OUTRA FORMA ATRAVÉS DO USO DO COMPLEMENTO GOOGLE TV É DE SUA INTEIRA RESPONSABILIDADE E RISCO, E VOCÊ É O ÚNICO RESPONSÁVEL POR QUALQUER DANO AO SEU SISTEMA DE COMPUTADOR OU OUTRO DISPOSITIVO OU PERDA DE DADOS QUE RESULTE DE TAL USO.
2026-05-17T18:43:05.1606923Z
2026-05-17T18:43:05.1608516Z 10.3 O GOOGLE EXPRESSAMENTE SE EXIME DE TODAS AS GARANTIAS E CONDIÇÕES DE QUALQUER TIPO, SEJAM ELAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS E CONDIÇÕES IMPLÍCITAS DE COMERCIABILIDADE, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO.
2026-05-17T18:43:05.1610287Z
2026-05-17T18:43:05.1610690Z 11. LIMITAÇÃO DE RESPONSABILIDADE
2026-05-17T18:43:05.1611066Z
2026-05-17T18:43:05.1613679Z 11.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O GOOGLE, SUAS SUBSIDIÁRIAS E AFILIADAS, E SEUS LICENCIADORES NÃO SERÃO RESPONSÁVEIS PERANTE VOCÊ SOB QUALQUER TEORIA DE RESPONSABILIDADE POR QUAISQUER DANOS DIRETOS, INDIRETOS, INCIDENTAIS, ESPECIAIS, CONSEQUENCIAIS OU EXEMPLARES QUE POSSAM SER INCORRIDOS POR VOCÊ, INCLUINDO QUALQUER PERDA DE DADOS, INDEPENDENTEMENTE DE O GOOGLE OU SEUS REPRESENTANTES TEREM SIDO AVISADOS OU DEVESSEM ESTAR CIENTES DA POSSIBILIDADE DE TAIS PERDAS OCORRER.
2026-05-17T18:43:05.1616475Z
2026-05-17T18:43:05.1616714Z 12. Indenização
2026-05-17T18:43:05.1617462Z
2026-05-17T18:43:05.1621921Z 12.1 Na máxima extensão permitida por lei, você concorda em defender, indenizar e isentar o Google, suas afiliadas e seus respectivos diretores, executivos, funcionários e agentes de quaisquer reivindicações, ações, processos ou procedimentos, bem como quaisquer perdas, responsabilidades, danos, custos e despesas (incluindo honorários advocatícios razoáveis) decorrentes de ou resultantes de (a) seu uso do complemento do Google TV, (b) qualquer aplicativo que você desenvolva no complemento do Google TV que infrinja qualquer direito autoral, marca registrada, segredo comercial, imagem comercial, patente ou outro direito de propriedade intelectual de qualquer pessoa ou difame qualquer pessoa ou viole seus direitos de publicidade ou privacidade, e (c) qualquer descumprimento por você deste Contrato de Licença.
2026-05-17T18:43:05.1626004Z
2026-05-17T18:43:05.1626283Z 13. Alterações ao Contrato de Licença
2026-05-17T18:43:05.1626705Z
2026-05-17T18:43:05.1627325Z 13.1 O Google poderá fazer alterações ao Contrato de Licença à medida que distribuir novas versões do complemento do Google TV.
2026-05-17T18:43:05.1628091Z
2026-05-17T18:43:05.1628341Z 14. Termos Legais Gerais
2026-05-17T18:43:05.1628668Z
2026-05-17T18:43:05.1630726Z 14.1 Este Contrato de Licença constitui o acordo legal integral entre você e o Google e rege seu uso do Complemento Google TV (excluindo quaisquer serviços que o Google possa fornecer a você sob um contrato escrito separado), e substitui completamente quaisquer acordos anteriores entre você e o Google em relação ao Complemento Google TV.
2026-05-17T18:43:05.1632865Z
2026-05-17T18:43:05.1634785Z 14.2 Você concorda que, se o Google não exercer ou fizer valer qualquer direito ou recurso legal contido neste Contrato de Licença (ou do qual o Google se beneficie sob qualquer lei aplicável), isso não será considerado uma renúncia formal dos direitos do Google e que esses direitos ou recursos ainda estarão disponíveis para o Google.
2026-05-17T18:43:05.1636861Z
2026-05-17T18:43:05.1638908Z 14.3 Se qualquer tribunal competente para decidir sobre esta matéria declarar que qualquer disposição deste Contrato de Licença é inválida, essa disposição será removida deste Contrato de Licença sem afetar o restante do mesmo. As demais disposições deste Contrato de Licença permanecerão válidas e em pleno vigor.
2026-05-17T18:43:05.1641222Z
2026-05-17T18:43:05.1644658Z 14.4 Você reconhece e concorda que os licenciadores de dados da API do Google e cada membro do grupo de empresas do qual o Google é a controladora serão terceiros beneficiários deste Contrato de Licença e que tais outras empresas terão o direito de exigir o cumprimento e se basear diretamente em qualquer disposição deste Contrato de Licença que lhes confira um benefício (ou direitos em seu favor). Além disso, nenhuma outra pessoa ou empresa será considerada terceira beneficiária deste Contrato de Licença.
2026-05-17T18:43:05.1647762Z
2026-05-17T18:43:05.1649692Z 14.5 RESTRIÇÕES DE EXPORTAÇÃO. O COMPLEMENTO GOOGLE TV ESTÁ SUJEITO ÀS LEIS E REGULAMENTOS DE EXPORTAÇÃO DOS ESTADOS UNIDOS. VOCÊ DEVE CUMPRIR TODAS AS LEIS E REGULAMENTOS DE EXPORTAÇÃO NACIONAIS E INTERNACIONAIS APLICÁVEIS AO COMPLEMENTO GOOGLE TV. ESSAS LEIS INCLUEM RESTRIÇÕES QUANTO A DESTINOS, USUÁRIOS FINAIS E USO FINAL.
2026-05-17T18:43:05.1651925Z
2026-05-17T18:43:05.1654022Z 14.6 Os direitos concedidos neste Contrato de Licença não podem ser cedidos ou transferidos por você ou pelo Google sem a prévia aprovação por escrito da outra parte. Nem você nem o Google poderão delegar suas responsabilidades ou obrigações sob este Contrato de Licença sem a prévia aprovação por escrito da outra parte.
2026-05-17T18:43:05.1656143Z
2026-05-17T18:43:05.1659773Z 14.7 Este Contrato de Licença e sua relação com o Google sob este Contrato de Licença serão regidos pelas leis do Estado da Califórnia, sem levar em consideração suas disposições sobre conflito de leis. Você e o Google concordam em se submeter à jurisdição exclusiva dos tribunais localizados no condado de Santa Clara, Califórnia, para resolver qualquer questão legal decorrente deste Contrato de Licença. Não obstante, você concorda que o Google ainda poderá solicitar medidas cautelares (ou um tipo equivalente de tutela jurisdicional urgente) em qualquer jurisdição.
2026-05-17T18:43:05.1663521Z
2026-05-17T18:43:05.1663653Z
2026-05-17T18:43:05.1663906Z 15 de agosto de 2011
2026-05-17T18:43:05.1664344Z ---------------------------------------
2026-05-17T18:43:05.1664902Z Aceitar? (s/N):
2026-05-17T18:43:05.1665360Z 2/6: Licença android-googlexr-license:
2026-05-17T18:43:05.1665900Z ---------------------------------------
Para começar a usar o SDK de Imagem do Sistema do Emulador Android XR, você deve concordar com os seguintes termos e condições. Conforme descrito abaixo, observe que esta é uma versão emulada e de pré-visualização do sistema operacional Android XR, sujeita a alterações, e que você usa por sua conta e risco.
2026-05-17T18:43:05.1669385Z
2026-05-17T18:43:05.1669796Z Este é o Contrato de Licença do SDK da Imagem do Sistema do Emulador Android XR
2026-05-17T18:43:05.1670516Z
2026-05-17T18:43:05.1670762Z 1. Introdução
2026-05-17T18:43:05.1671072Z
2026-05-17T18:43:05.1673702Z 1.1 O SDK de Imagem do Sistema do Emulador Android XR (referido no Contrato de Licença como "SDK" e incluindo especificamente os arquivos do sistema Android, APIs empacotadas, arquivos de biblioteca (se e quando disponibilizados) e aplicativos e complementos de APIs do Google) é licenciado para você sujeito aos termos do Contrato de Licença. O Contrato de Licença constitui um contrato juridicamente vinculativo entre você e o Google em relação ao seu uso do SDK.
2026-05-17T18:43:05.1676381Z
2026-05-17T18:43:05.1677463Z 1.2 "Android" significa a pilha de software Android para dispositivos, disponibilizada pelo Projeto de Código Aberto do Android, que está localizado no seguinte URL: https://source.android.com/, e que é atualizada periodicamente.
2026-05-17T18:43:05.1678655Z
2026-05-17T18:43:05.1679779Z 1.3 "Google" significa Google LLC, organizada sob as leis do Estado de Delaware, EUA, e operando sob as leis dos EUA, com sede principal em 1600 Amphitheatre Parkway, Mountain View, CA 94043, EUA.
2026-05-17T18:43:05.1681515Z
2026-05-17T18:43:05.1681814Z 2. Aceitação deste Contrato de Licença
2026-05-17T18:43:05.1682213Z
2026-05-17T18:43:05.1683025Z 2.1 Para usar o SDK, você deve primeiro concordar com o Contrato de Licença. Você não poderá usar o SDK se não aceitar o Contrato de Licença.
2026-05-17T18:43:05.1684032Z
2026-05-17T18:43:05.1684636Z 2.2 Ao clicar em aceitar e/ou usar este SDK, você concorda com os termos do Contrato de Licença.
2026-05-17T18:43:05.1685409Z
2026-05-17T18:43:05.1686915Z 2.3 Você não poderá usar o SDK nem aceitar o Contrato de Licença se for uma pessoa impedida de receber o SDK de acordo com as leis dos Estados Unidos ou de outros países, incluindo o país em que você reside ou de onde você usa o SDK.
2026-05-17T18:43:05.1688496Z
2026-05-17T18:43:05.1690772Z 2.4 Se você concordar em se vincular ao Contrato de Licença em nome de seu empregador ou outra entidade, você declara e garante que possui plena autoridade legal para vincular seu empregador ou tal entidade ao Contrato de Licença. Caso não possua a autoridade necessária, você não poderá aceitar o Contrato de Licença nem usar o SDK em nome de seu empregador ou outra entidade.
2026-05-17T18:43:05.1693461Z
2026-05-17T18:43:05.1693737Z 3. Licença do SDK do Google
2026-05-17T18:43:05.1694115Z
2026-05-17T18:43:05.1695495Z 3.1 Sujeito aos termos do Contrato de Licença, o Google concede a você uma licença limitada, mundial, isenta de royalties, não atribuível, não exclusiva e não sublicenciável para usar o SDK exclusivamente para desenvolver aplicativos para Android XR.
2026-05-17T18:43:05.1697099Z
2026-05-17T18:43:05.1698375Z 3.2 Você não pode usar este SDK para desenvolver aplicativos para outras plataformas ou para desenvolver outro SDK. É claro que você tem a liberdade de desenvolver aplicativos para outras plataformas, desde que este SDK não seja usado para esse fim.
2026-05-17T18:43:05.1699821Z
2026-05-17T18:43:05.1702555Z 3.3 Você concorda que o Google ou terceiros detêm todos os direitos legais, títulos e interesses relativos ao SDK, incluindo quaisquer Direitos de Propriedade Intelectual que subsistam no SDK. "Direitos de Propriedade Intelectual" significa todos e quaisquer direitos sob a lei de patentes, lei de direitos autorais, lei de segredos comerciais, lei de marcas registradas e quaisquer outros direitos de propriedade. O Google reserva-se todos os direitos não expressamente concedidos a você.
2026-05-17T18:43:05.1705101Z
2026-05-17T18:43:05.1708446Z 3.4 Você não pode usar o SDK para qualquer finalidade que não seja expressamente permitida pelo Contrato de Licença. Exceto na medida exigida por licenças de terceiros aplicáveis, você não pode (a) copiar (exceto para fins de backup), modificar, adaptar, redistribuir, descompilar, fazer engenharia reversa, desmontar ou criar trabalhos derivados do SDK ou de qualquer parte do SDK; ou (b) carregar qualquer parte do SDK em um dispositivo móvel ou qualquer outro dispositivo de hardware, exceto um computador pessoal, combinar qualquer parte do SDK com outro software ou distribuir qualquer software ou dispositivo que incorpore uma parte do SDK.
2026-05-17T18:43:05.1712093Z
2026-05-17T18:43:05.1714679Z 3.5 O uso, a reprodução e a distribuição de componentes do SDK licenciados sob uma licença de software de código aberto são regidos exclusivamente pelos termos dessa licença de software de código aberto e não pelo Contrato de Licença. Você concorda em permanecer um licenciado em situação regular em relação a essas licenças de software de código aberto, sob todos os direitos concedidos, e em se abster de quaisquer ações que possam rescindir, suspender ou violar tais direitos.
2026-05-17T18:43:05.1717467Z
2026-05-17T18:43:05.1720060Z 3.6 Você concorda que a forma e a natureza do SDK fornecido pelo Google podem ser alteradas sem aviso prévio e que versões futuras do SDK podem ser incompatíveis com aplicativos desenvolvidos em versões anteriores do SDK. Você concorda que o Google pode interromper (permanentemente ou temporariamente) o fornecimento do SDK (ou de quaisquer recursos dentro do SDK) para você ou para os usuários em geral, a critério exclusivo do Google, sem aviso prévio.
2026-05-17T18:43:05.1722936Z
2026-05-17T18:43:05.1724025Z 3.7 Nada no Contrato de Licença lhe dá o direito de usar quaisquer nomes comerciais, marcas registradas, marcas de serviço, logotipos, nomes de domínio ou outras características distintivas da marca do Google.
2026-05-17T18:43:05.1725244Z
2026-05-17T18:43:05.1726369Z 3.8 Você concorda em não remover, ocultar ou alterar quaisquer avisos de direitos de propriedade (incluindo avisos de direitos autorais e marcas registradas) que possam estar afixados ou contidos no SDK.
2026-05-17T18:43:05.1727686Z
2026-05-17T18:43:05.1727935Z 4. Uso do SDK por você
2026-05-17T18:43:05.1728278Z
2026-05-17T18:43:05.1729921Z 4.1 O Google concorda que não obtém nenhum direito, título ou interesse seu (ou de seus licenciadores) sob o Contrato de Licença em relação a quaisquer aplicativos de software que você desenvolva usando o SDK, incluindo quaisquer direitos de propriedade intelectual que existam nesses aplicativos.
2026-05-17T18:43:05.1731875Z
2026-05-17T18:43:05.1734033Z 4.2 Você concorda em usar o SDK e escrever aplicativos apenas para fins permitidos por (a) o Contrato de Licença e (b) qualquer lei, regulamento ou práticas ou diretrizes geralmente aceitas aplicáveis ​​nas jurisdições relevantes (incluindo quaisquer leis relativas à exportação de dados ou software de e para os Estados Unidos ou outros países relevantes).
2026-05-17T18:43:05.1736517Z
2026-05-17T18:43:05.1741418Z 4.3 Você concorda que, se usar o SDK para desenvolver aplicativos para usuários do público em geral, protegerá a privacidade e os direitos legais desses usuários. Se os usuários fornecerem nomes de usuário, senhas ou outras informações de login ou informações pessoais, você deverá informá-los de que essas informações estarão disponíveis para o seu aplicativo e deverá fornecer um aviso de privacidade e proteção legalmente adequados para esses usuários. Se o seu aplicativo armazenar informações pessoais ou confidenciais fornecidas pelos usuários, deverá fazê-lo de forma segura. Se o usuário fornecer ao seu aplicativo informações da Conta do Google, seu aplicativo poderá usar essas informações somente para acessar a Conta do Google do usuário quando e para os fins limitados para os quais o usuário lhe tiver dado permissão para fazê-lo.
2026-05-17T18:43:05.1746280Z
2026-05-17T18:43:05.1748688Z 4.4 Você concorda que não se envolverá em nenhuma atividade com o SDK, incluindo o desenvolvimento ou distribuição de um aplicativo, que interfira, interrompa, danifique ou acesse de forma não autorizada os servidores, redes ou outras propriedades ou serviços de terceiros, incluindo, entre outros, o Google ou qualquer operadora de comunicação móvel.
2026-05-17T18:43:05.1751274Z
2026-05-17T18:43:05.1753372Z 4.5 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) quaisquer dados, conteúdo ou recursos que você criar, transmitir ou exibir por meio do Android e/ou aplicativos para Android, e pelas consequências de suas ações (incluindo qualquer perda ou dano que o Google possa sofrer) ao fazê-lo.
2026-05-17T18:43:05.1755646Z
2026-05-17T18:43:05.1758077Z 4.6 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) qualquer violação de suas obrigações sob o Contrato de Licença, qualquer contrato de terceiros aplicável ou Termos de Serviço, ou qualquer lei ou regulamento aplicável, e pelas consequências (incluindo qualquer perda ou dano que o Google ou terceiros possam sofrer) de tal violação.
2026-05-17T18:43:05.1760677Z
2026-05-17T18:43:05.1762474Z 4.7 O SDK está em desenvolvimento, e seus testes e feedback são uma parte importante do processo de desenvolvimento. Ao usar o SDK, você reconhece que a implementação de alguns recursos ainda está em desenvolvimento e que você não deve esperar que o SDK tenha todas as funcionalidades de uma versão estável.
2026-05-17T18:43:05.1764440Z
2026-05-17T18:43:05.1764719Z 5. Suas credenciais de desenvolvedor
2026-05-17T18:43:05.1765105Z
2026-05-17T18:43:05.1766790Z 5.1 Você concorda que é responsável por manter a confidencialidade de quaisquer credenciais de desenvolvedor que possam ser emitidas para você pelo Google ou que você mesmo escolha, e que será o único responsável por todos os aplicativos desenvolvidos com suas credenciais de desenvolvedor.
2026-05-17T18:43:05.1768643Z
2026-05-17T18:43:05.1768928Z 6. Privacidade e Informações
2026-05-17T18:43:05.1769287Z
2026-05-17T18:43:05.1772252Z 6.1 Para inovar e aprimorar continuamente o SDK, o Google poderá coletar determinadas estatísticas de uso do software, incluindo, entre outras, um identificador exclusivo, o endereço IP associado, o número da versão do software e informações sobre quais ferramentas e/ou serviços do SDK estão sendo usados ​​e como estão sendo usados. Antes que qualquer uma dessas informações seja coletada, o SDK notificará você e solicitará seu consentimento. Caso você negue o consentimento, as informações não serão coletadas.
2026-05-17T18:43:05.1775323Z
2026-05-17T18:43:05.1776579Z 6.2 Os dados coletados são analisados ​​de forma agregada para aprimorar o SDK e são mantidos de acordo com a Política de Privacidade do Google, disponível no seguinte endereço: https://policies.google.com/privacy
2026-05-17T18:43:05.1777953Z
2026-05-17T18:43:05.1778538Z 6.3 Conjuntos de dados anonimizados e agregados podem ser compartilhados com parceiros do Google para aprimorar o SDK.
2026-05-17T18:43:05.1779495Z
2026-05-17T18:43:05.1779765Z 7. Aplicativos de terceiros
2026-05-17T18:43:05.1780128Z
2026-05-17T18:43:05.1782794Z 7.1 Se você usar o SDK para executar aplicativos desenvolvidos por terceiros ou que acessem dados, conteúdo ou recursos fornecidos por terceiros, você concorda que o Google não é responsável por esses aplicativos, dados, conteúdo ou recursos. Você entende que todos os dados, conteúdo ou recursos aos quais você possa acessar por meio desses aplicativos de terceiros são de responsabilidade exclusiva da pessoa que os originou e que o Google não é responsável por qualquer perda ou dano que você possa sofrer como resultado do uso ou acesso a quaisquer desses aplicativos, dados, conteúdo ou recursos de terceiros.
2026-05-17T18:43:05.1784703Z
2026-05-17T18:43:05.1786215Z 7.2 Você deve estar ciente de que os dados, o conteúdo e os recursos apresentados a você por meio de um aplicativo de terceiros podem estar protegidos por direitos de propriedade intelectual pertencentes aos provedores (ou a outras pessoas ou empresas em seu nome). Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados, conteúdo ou recursos (no todo ou em parte), a menos que tenha recebido permissão expressa dos respectivos proprietários.
2026-05-17T18:43:05.1787678Z
2026-05-17T18:43:05.1788439Z 7.3 Você reconhece que o uso de aplicativos, dados, conteúdo ou recursos de terceiros pode estar sujeito a termos separados entre você e o respectivo terceiro. Nesse caso, o Contrato de Licença não afeta sua relação jurídica com esses terceiros.
2026-05-17T18:43:05.1789270Z
2026-05-17T18:43:05.1789350Z 8. Usando APIs do Android
2026-05-17T18:43:05.1789479Z
2026-05-17T18:43:05.1789549Z 8.1 APIs de dados do Google
2026-05-17T18:43:05.1789665Z
2026-05-17T18:43:05.1791246Z 8.1.1 Se você usar qualquer API para obter dados do Google, você reconhece que os dados podem estar protegidos por direitos de propriedade intelectual pertencentes ao Google ou às partes que fornecem os dados (ou a outras pessoas ou empresas em nome delas). O uso de qualquer API desse tipo pode estar sujeito a Termos de Serviço adicionais. Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados (no todo ou em parte), a menos que seja permitido pelos Termos de Serviço relevantes.
2026-05-17T18:43:05.1792717Z
2026-05-17T18:43:05.1795224Z 8.1.2 Se você usar qualquer API para recuperar dados de um usuário do Google, você reconhece e concorda que só poderá recuperar dados com o consentimento explícito do usuário e somente quando, e para os fins limitados para os quais, o usuário lhe concedeu permissão para fazê-lo. Se você usar a API do Serviço de Reconhecimento do Android, documentada no seguinte URL: https://developer.android.com/reference/android/speech/RecognitionService, conforme atualizada periodicamente, você reconhece que o uso da API está sujeito ao Adendo de Processamento de Dados para Produtos nos quais o Google é um Processador de Dados, que pode ser encontrado no seguinte URL: https://privacy.google.com/businesses/gdprprocessorterms/, conforme atualizado periodicamente. Ao clicar em "Aceitar", você concorda com os termos do Adendo de Processamento de Dados para Produtos nos quais o Google é um Processador de Dados.
2026-05-17T18:43:05.1798380Z
2026-05-17T18:43:05.1798489Z 9. Rescisão deste Contrato de Licença
2026-05-17T18:43:05.1798652Z
2026-05-17T18:43:05.1798920Z 9.1 O Contrato de Licença continuará em vigor até ser rescindido por você ou pelo Google, conforme estabelecido abaixo.
2026-05-17T18:43:05.1799282Z
2026-05-17T18:43:05.1799619Z 9.2 Se desejar rescindir o Contrato de Licença, poderá fazê-lo cessando a utilização do SDK e quaisquer credenciais de desenvolvedor relevantes.
2026-05-17T18:43:05.1800032Z
2026-05-17T18:43:05.1802019Z 9.3 O Google poderá, a qualquer momento, rescindir o Contrato de Licença com você se: (A) você violar qualquer disposição do Contrato de Licença; ou (B) o Google for obrigado a fazê-lo por lei; ou (C) o parceiro com quem o Google ofereceu determinadas partes do SDK (como APIs) a você tiver encerrado seu relacionamento com o Google ou deixado de oferecer determinadas partes do SDK a você; ou (D) o Google decidir não fornecer mais o SDK ou determinadas partes do SDK aos usuários no país em que você reside ou de onde você usa o serviço, ou se o fornecimento do SDK ou de determinados serviços do SDK a você pelo Google, a critério exclusivo do Google, deixar de ser comercialmente viável.
2026-05-17T18:43:05.1803990Z
2026-05-17T18:43:05.1805267Z 9.4 Quando o Contrato de Licença chegar ao fim, todos os direitos, obrigações e responsabilidades legais que você e o Google tenham usufruído, aos quais tenham estado sujeitos (ou que tenham se acumulado ao longo do tempo enquanto o Contrato de Licença esteve em vigor) ou que expressamente devam continuar indefinidamente, não serão afetados por esta rescisão, e as disposições do parágrafo 14.7 continuarão a se aplicar a tais direitos, obrigações e responsabilidades indefinidamente.
2026-05-17T18:43:05.1806604Z
2026-05-17T18:43:05.1806702Z 10. ISENÇÃO DE GARANTIAS
2026-05-17T18:43:05.1806846Z
2026-05-17T18:43:05.1807364Z 10.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O USO DO SDK É POR SUA CONTA E RISCO E QUE O SDK É FORNECIDO "NO ESTADO EM QUE SE ENCONTRA" E "CONFORME DISPONÍVEL", SEM QUALQUER GARANTIA DO GOOGLE.
2026-05-17T18:43:05.1807919Z
2026-05-17T18:43:05.1808633Z 10.2 O USO DO SDK E DE QUALQUER MATERIAL BAIXADO OU OBTIDO DE OUTRA FORMA ATRAVÉS DO USO DO SDK É DE SUA INTEIRA RESPONSABILIDADE E RISCO, E VOCÊ É O ÚNICO RESPONSÁVEL POR QUALQUER DANO AO SEU SISTEMA DE COMPUTADOR OU OUTRO DISPOSITIVO OU PERDA DE DADOS QUE RESULTE DE TAL USO.
2026-05-17T18:43:05.1809437Z
2026-05-17T18:43:05.1810164Z 10.3 O GOOGLE EXPRESSAMENTE SE EXIME DE TODAS AS GARANTIAS E CONDIÇÕES DE QUALQUER TIPO, SEJAM ELAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS E CONDIÇÕES IMPLÍCITAS DE COMERCIABILIDADE, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO.
2026-05-17T18:43:05.1811090Z
2026-05-17T18:43:05.1811169Z 11. LIMITAÇÃO DE RESPONSABILIDADE
2026-05-17T18:43:05.1811310Z
2026-05-17T18:43:05.1812562Z 11.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O GOOGLE, SUAS SUBSIDIÁRIAS E AFILIADAS, E SEUS LICENCIADORES NÃO SERÃO RESPONSÁVEIS PERANTE VOCÊ SOB QUALQUER TEORIA DE RESPONSABILIDADE POR QUAISQUER DANOS DIRETOS, INDIRETOS, INCIDENTAIS, ESPECIAIS, CONSEQUENCIAIS OU EXEMPLARES QUE POSSAM SER INCORRIDOS POR VOCÊ, INCLUINDO QUALQUER PERDA DE DADOS, INDEPENDENTEMENTE DE O GOOGLE OU SEUS REPRESENTANTES TEREM SIDO AVISADOS OU DEVESSEM ESTAR CIENTES DA POSSIBILIDADE DE TAIS PERDAS OCORRER.
2026-05-17T18:43:05.1813880Z
2026-05-17T18:43:05.1813951Z 12. Indenização
2026-05-17T18:43:05.1814062Z
2026-05-17T18:43:05.1816148Z 12.1 Na máxima extensão permitida por lei, você concorda em defender, indenizar e isentar o Google, suas afiliadas e seus respectivos diretores, executivos, funcionários e agentes de quaisquer reivindicações, ações, processos ou procedimentos, bem como quaisquer perdas, responsabilidades, danos, custos e despesas (incluindo honorários advocatícios razoáveis) decorrentes de ou resultantes de (a) seu uso do SDK, (b) qualquer aplicativo que você desenvolva no SDK que infrinja qualquer direito autoral, marca registrada, segredo comercial, imagem comercial, patente ou outro direito de propriedade intelectual de qualquer pessoa ou difame qualquer pessoa ou viole seus direitos de publicidade ou privacidade, e (c) qualquer descumprimento por você do Contrato de Licença.
2026-05-17T18:43:05.1818282Z
2026-05-17T18:43:05.1818379Z 13. Alterações ao Contrato de Licença
2026-05-17T18:43:05.1818530Z
2026-05-17T18:43:05.1819203Z 13.1 O Google poderá fazer alterações ao Contrato de Licença ao distribuir novas versões do SDK. Quando essas alterações forem feitas, o Google disponibilizará uma nova versão do Contrato de Licença no site onde o SDK é disponibilizado.
2026-05-17T18:43:05.1819931Z
2026-05-17T18:43:05.1820004Z 14. Termos Legais Gerais
2026-05-17T18:43:05.1820128Z
2026-05-17T18:43:05.1821104Z 14.1 O Contrato de Licença constitui o acordo legal integral entre você e o Google e rege seu uso do SDK (excluindo quaisquer serviços que o Google possa fornecer a você sob um contrato escrito separado), e substitui completamente quaisquer acordos anteriores entre você e o Google em relação ao SDK.
2026-05-17T18:43:05.1822106Z
2026-05-17T18:43:05.1822982Z 14.2 Você concorda que, se o Google não exercer ou fizer valer qualquer direito ou recurso legal contido no Contrato de Licença (ou do qual o Google se beneficie de acordo com qualquer lei aplicável), isso não será considerado uma renúncia formal dos direitos do Google e que esses direitos ou recursos ainda estarão disponíveis para o Google.
2026-05-17T18:43:05.1823947Z
2026-05-17T18:43:05.1824908Z 14.3 Se qualquer tribunal competente para decidir sobre esta matéria declarar que qualquer disposição do Contrato de Licença é inválida, essa disposição será removida do Contrato de Licença sem afetar o restante do Contrato de Licença. As demais disposições do Contrato de Licença continuarão válidas e em vigor.
2026-05-17T18:43:05.1825964Z
2026-05-17T18:43:05.1827290Z 14.4 Você reconhece e concorda que cada membro do grupo de empresas do qual o Google é a controladora será considerado terceiro beneficiário do Contrato de Licença e que tais outras empresas terão o direito de exigir o cumprimento e se valer diretamente de qualquer disposição do Contrato de Licença que lhes confira um benefício (ou direitos em seu favor). Além disso, nenhuma outra pessoa ou empresa será considerada terceiro beneficiário do Contrato de Licença.
2026-05-17T18:43:05.1828633Z
2026-05-17T18:43:05.1829367Z 14.5 RESTRIÇÕES DE EXPORTAÇÃO. O SDK ESTÁ SUJEITO ÀS LEIS E REGULAMENTOS DE EXPORTAÇÃO DOS ESTADOS UNIDOS. VOCÊ DEVE CUMPRIR TODAS AS LEIS E REGULAMENTOS DE EXPORTAÇÃO NACIONAIS E INTERNACIONAIS APLICÁVEIS AO SDK. ESSAS LEIS INCLUEM RESTRIÇÕES QUANTO A DESTINOS, USUÁRIOS FINAIS E USO FINAL.
2026-05-17T18:43:05.1830181Z
2026-05-17T18:43:05.1831269Z 14.6 Os direitos concedidos no Contrato de Licença não podem ser cedidos ou transferidos por você ou pelo Google sem a prévia aprovação por escrito da outra parte. Nem você nem o Google poderão delegar suas responsabilidades ou obrigações sob o Contrato de Licença sem a prévia aprovação por escrito da outra parte.
2026-05-17T18:43:05.1832317Z
2026-05-17T18:43:05.1833969Z 14.7 O Contrato de Licença e sua relação com o Google sob o Contrato de Licença serão regidos pelas leis do Estado da Califórnia, sem levar em consideração suas disposições sobre conflito de leis. Você e o Google concordam em se submeter à jurisdição exclusiva dos tribunais localizados no condado de Santa Clara, Califórnia, para resolver qualquer questão legal decorrente do Contrato de Licença. Não obstante, você concorda que o Google ainda poderá solicitar medidas cautelares (ou um tipo equivalente de tutela jurisdicional urgente) em qualquer jurisdição.
2026-05-17T18:43:05.1835729Z ---------------------------------------
2026-05-17T18:43:05.1835958Z Aceitar? (s/N):
2026-05-17T18:43:05.1836155Z 3/6: Licença android-sdk-arm-dbt-license:
2026-05-17T18:43:05.1836409Z ---------------------------------------
2026-05-17T18:43:05.1836635Z Termos e Condições
2026-05-17T18:43:05.1836747Z
2026-05-17T18:43:05.1836892Z Este é o Contrato de Licença do Kit de Desenvolvimento de Software Android .
2026-05-17T18:43:05.1837112Z
2026-05-17T18:43:05.1837187Z 1. Introdução
2026-05-17T18:43:05.1837286Z
2026-05-17T18:43:05.1838308Z 1.1 O Kit de Desenvolvimento de Software Android (referido no Contrato de Licença como "SDK" e incluindo especificamente os arquivos do sistema Android, APIs empacotadas e complementos das APIs do Google) é licenciado para você sujeito aos termos do Contrato de Licença. O Contrato de Licença constitui um contrato juridicamente vinculativo entre você e o Google em relação ao seu uso do SDK.
2026-05-17T18:43:05.1839406Z
2026-05-17T18:43:05.1839993Z 1.2 "Android" significa a pilha de software Android para dispositivos, disponibilizada pelo Projeto de Código Aberto do Android, que está localizado no seguinte URL: http://source.android.com/, e que é atualizada periodicamente.
2026-05-17T18:43:05.1840825Z
2026-05-17T18:43:05.1841837Z 1.3 Uma "implementação compatível" significa qualquer dispositivo Android que (i) esteja em conformidade com o documento de Definição de Compatibilidade do Android, que pode ser encontrado no site de compatibilidade do Android (http://source.android.com/compatibility) e que pode ser atualizado de tempos em tempos; e (ii) passe com sucesso no Conjunto de Testes de Compatibilidade do Android (CTS).
2026-05-17T18:43:05.1842972Z
2026-05-17T18:43:05.1843397Z 1.4 "Google" significa Google Inc., uma corporação de Delaware com sede principal em 1600 Amphitheatre Parkway, Mountain View, CA 94043, Estados Unidos.
2026-05-17T18:43:05.1843891Z
2026-05-17T18:43:05.1843895Z
2026-05-17T18:43:05.1843983Z 2. Aceitação do Contrato de Licença
2026-05-17T18:43:05.1844140Z
2026-05-17T18:43:05.1844484Z 2.1 Para usar o SDK, você deve primeiro concordar com o Contrato de Licença. Você não poderá usar o SDK se não aceitar o Contrato de Licença.
2026-05-17T18:43:05.1844913Z
2026-05-17T18:43:05.1845105Z 2.2 Ao clicar em aceitar, você concorda com os termos do Contrato de Licença.
2026-05-17T18:43:05.1845372Z
2026-05-17T18:43:05.1846099Z 2.3 Você não poderá usar o SDK nem aceitar o Contrato de Licença se for uma pessoa impedida de receber o SDK de acordo com as leis dos Estados Unidos ou de outros países, incluindo o país em que você reside ou de onde você usa o SDK.
2026-05-17T18:43:05.1846859Z
2026-05-17T18:43:05.1848202Z 2.4 Se você concordar em se vincular ao Contrato de Licença em nome de seu empregador ou outra entidade, você declara e garante que possui plena autoridade legal para vincular seu empregador ou tal entidade ao Contrato de Licença. Caso não possua a autoridade necessária, você não poderá aceitar o Contrato de Licença nem usar o SDK em nome de seu empregador ou outra entidade.
2026-05-17T18:43:05.1849843Z
2026-05-17T18:43:05.1849848Z
2026-05-17T18:43:05.1849960Z 3. Licença do SDK do Google
2026-05-17T18:43:05.1850154Z
2026-05-17T18:43:05.1851336Z 3.1 Sujeito aos termos do Contrato de Licença, o Google concede a você uma licença limitada, mundial, isenta de royalties, não atribuível, não exclusiva e não sublicenciável para usar o SDK exclusivamente para desenvolver aplicativos para implementações compatíveis com o Android.
2026-05-17T18:43:05.1852643Z
2026-05-17T18:43:05.1854155Z 3.2 Você não pode usar este SDK para desenvolver aplicativos para outras plataformas (incluindo implementações não compatíveis do Android) ou para desenvolver outro SDK. É claro que você tem a liberdade de desenvolver aplicativos para outras plataformas, incluindo implementações não compatíveis do Android, desde que este SDK não seja usado para esse fim.
2026-05-17T18:43:05.1856055Z
2026-05-17T18:43:05.1858095Z 3.3 Você concorda que o Google ou terceiros detêm todos os direitos legais, títulos e interesses relativos ao SDK, incluindo quaisquer Direitos de Propriedade Intelectual que subsistam no SDK. "Direitos de Propriedade Intelectual" significa todos e quaisquer direitos sob a lei de patentes, lei de direitos autorais, lei de segredos comerciais, lei de marcas registradas e quaisquer outros direitos de propriedade. O Google reserva-se todos os direitos não expressamente concedidos a você.
2026-05-17T18:43:05.1860048Z
2026-05-17T18:43:05.1861757Z 3.4 Você não pode usar o SDK para qualquer finalidade que não seja expressamente permitida pelo Contrato de Licença. Exceto na medida exigida por licenças de terceiros aplicáveis, você não pode copiar (exceto para fins de backup), modificar, adaptar, redistribuir, descompilar, fazer engenharia reversa, desmontar ou criar trabalhos derivados do SDK ou de qualquer parte do SDK.
2026-05-17T18:43:05.1863603Z
2026-05-17T18:43:05.1864591Z 3.5 O uso, a reprodução e a distribuição de componentes do SDK licenciados sob uma licença de software de código aberto são regidos exclusivamente pelos termos dessa licença de software de código aberto e não pelo Contrato de Licença.
2026-05-17T18:43:05.1865693Z
2026-05-17T18:43:05.1867881Z 3.6 Você concorda que a forma e a natureza do SDK fornecido pelo Google podem ser alteradas sem aviso prévio e que versões futuras do SDK podem ser incompatíveis com aplicativos desenvolvidos em versões anteriores do SDK. Você concorda que o Google pode interromper (permanentemente ou temporariamente) o fornecimento do SDK (ou quaisquer recursos dentro do SDK) para você ou para os usuários em geral, a critério exclusivo do Google, sem aviso prévio.
2026-05-17T18:43:05.1869399Z
2026-05-17T18:43:05.1869878Z 3.7 Nada no Contrato de Licença lhe dá o direito de usar quaisquer nomes comerciais, marcas registradas, marcas de serviço, logotipos, nomes de domínio ou outras características distintivas da marca do Google.
2026-05-17T18:43:05.1870571Z
2026-05-17T18:43:05.1871073Z 3.8 Você concorda em não remover, ocultar ou alterar quaisquer avisos de direitos de propriedade (incluindo avisos de direitos autorais e marcas registradas) que possam estar afixados ou contidos no SDK.
2026-05-17T18:43:05.1871666Z
2026-05-17T18:43:05.1871671Z
2026-05-17T18:43:05.1871754Z 4. Uso do SDK por você
2026-05-17T18:43:05.1871882Z
2026-05-17T18:43:05.1872621Z 4.1 O Google concorda que não obtém nenhum direito, título ou interesse seu (ou de seus licenciadores) sob o Contrato de Licença em relação a quaisquer aplicativos de software que você desenvolva usando o SDK, incluindo quaisquer direitos de propriedade intelectual que existam nesses aplicativos.
2026-05-17T18:43:05.1873431Z
2026-05-17T18:43:05.1874491Z 4.2 Você concorda em usar o SDK e escrever aplicativos apenas para fins permitidos por (a) o Contrato de Licença e (b) qualquer lei, regulamento ou práticas ou diretrizes geralmente aceitas aplicáveis ​​nas jurisdições relevantes (incluindo quaisquer leis relativas à exportação de dados ou software de e para os Estados Unidos ou outros países relevantes).
2026-05-17T18:43:05.1876002Z
2026-05-17T18:43:05.1879838Z 4.3 Você concorda que, se usar o SDK para desenvolver aplicativos para usuários do público em geral, protegerá a privacidade e os direitos legais desses usuários. Se os usuários fornecerem nomes de usuário, senhas ou outras informações de login ou informações pessoais, você deverá informá-los de que essas informações estarão disponíveis para o seu aplicativo e deverá fornecer um aviso de privacidade e proteção legalmente adequados para esses usuários. Se o seu aplicativo armazenar informações pessoais ou confidenciais fornecidas pelos usuários, deverá fazê-lo de forma segura. Se o usuário fornecer ao seu aplicativo informações da Conta do Google, seu aplicativo poderá usar essas informações somente para acessar a Conta do Google do usuário quando e para os fins limitados para os quais o usuário lhe tiver dado permissão para fazê-lo.
2026-05-17T18:43:05.1882776Z
2026-05-17T18:43:05.1883807Z 4.4 Você concorda que não se envolverá em nenhuma atividade com o SDK, incluindo o desenvolvimento ou distribuição de um aplicativo, que interfira, interrompa, danifique ou acesse de forma não autorizada os servidores, redes ou outras propriedades ou serviços de terceiros, incluindo, entre outros, o Google ou qualquer operadora de comunicação móvel.
2026-05-17T18:43:05.1884925Z
2026-05-17T18:43:05.1885890Z 4.5 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) quaisquer dados, conteúdo ou recursos que você criar, transmitir ou exibir por meio do Android e/ou aplicativos para Android, e pelas consequências de suas ações (incluindo qualquer perda ou dano que o Google possa sofrer) ao fazê-lo.
2026-05-17T18:43:05.1886943Z
2026-05-17T18:43:05.1888041Z 4.6 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) qualquer violação de suas obrigações sob o Contrato de Licença, qualquer contrato de terceiros aplicável ou Termos de Serviço, ou qualquer lei ou regulamento aplicável, e pelas consequências (incluindo qualquer perda ou dano que o Google ou terceiros possam sofrer) de tal violação.
2026-05-17T18:43:05.1889225Z
2026-05-17T18:43:05.1890840Z 4.7 Este software permite a execução de propriedade intelectual pertencente à Arm Limited. Você concorda que seu uso do software, que permite a execução de executáveis ​​compatíveis com a Arquitetura de Conjunto de Instruções ARM (“ISA”) para desenvolvimento e depuração de aplicativos, está sujeito aos termos e condições aqui descritos, exclusivamente em desktops x86, laptops, servidores locais do cliente e ambientes em nuvem adquiridos pelo cliente.
2026-05-17T18:43:05.1891970Z
2026-05-17T18:43:05.1892064Z 5. Suas credenciais de desenvolvedor
2026-05-17T18:43:05.1892206Z
2026-05-17T18:43:05.1893014Z 5.1 Você concorda que é responsável por manter a confidencialidade de quaisquer credenciais de desenvolvedor que possam ser emitidas para você pelo Google ou que você mesmo escolha, e que será o único responsável por todos os aplicativos desenvolvidos com suas credenciais de desenvolvedor.
2026-05-17T18:43:05.1894050Z
2026-05-17T18:43:05.1894131Z 6. Privacidade e Informações
2026-05-17T18:43:05.1894265Z
2026-05-17T18:43:05.1895643Z 6.1 Para inovar e aprimorar continuamente o SDK, o Google poderá coletar determinadas estatísticas de uso do software, incluindo, entre outras, um identificador exclusivo, o endereço IP associado, o número da versão do software e informações sobre quais ferramentas e/ou serviços do SDK estão sendo usados ​​e como estão sendo usados. Antes que qualquer uma dessas informações seja coletada, o SDK notificará você e solicitará seu consentimento. Caso você negue o consentimento, as informações não serão coletadas.
2026-05-17T18:43:05.1897098Z
2026-05-17T18:43:05.1897438Z 6.2 Os dados coletados são examinados de forma agregada para aprimorar o SDK e são mantidos de acordo com a Política de Privacidade do Google.
2026-05-17T18:43:05.1897858Z
2026-05-17T18:43:05.1897863Z
2026-05-17T18:43:05.1897946Z 7. Aplicativos de terceiros
2026-05-17T18:43:05.1898085Z
2026-05-17T18:43:05.1899832Z 7.1 Se você usar o SDK para executar aplicativos desenvolvidos por terceiros ou que acessem dados, conteúdo ou recursos fornecidos por terceiros, você concorda que o Google não é responsável por esses aplicativos, dados, conteúdo ou recursos. Você entende que todos os dados, conteúdo ou recursos aos quais você possa acessar por meio desses aplicativos de terceiros são de responsabilidade exclusiva da pessoa que os originou e que o Google não é responsável por qualquer perda ou dano que você possa sofrer como resultado do uso ou acesso a quaisquer desses aplicativos, dados, conteúdo ou recursos de terceiros.
2026-05-17T18:43:05.1901764Z
2026-05-17T18:43:05.1903138Z 7.2 Você deve estar ciente de que os dados, o conteúdo e os recursos apresentados a você por meio de um aplicativo de terceiros podem estar protegidos por direitos de propriedade intelectual pertencentes aos provedores (ou a outras pessoas ou empresas em seu nome). Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados, conteúdo ou recursos (no todo ou em parte), a menos que tenha recebido permissão expressa dos respectivos proprietários.
2026-05-17T18:43:05.1904575Z
2026-05-17T18:43:05.1905323Z 7.3 Você reconhece que o uso de aplicativos, dados, conteúdo ou recursos de terceiros pode estar sujeito a termos separados entre você e o respectivo terceiro. Nesse caso, o Contrato de Licença não afeta sua relação jurídica com esses terceiros.
2026-05-17T18:43:05.1906151Z
2026-05-17T18:43:05.1906156Z
2026-05-17T18:43:05.1906234Z 8. Usando APIs do Android
2026-05-17T18:43:05.1906356Z
2026-05-17T18:43:05.1906428Z 8.1 APIs de dados do Google
2026-05-17T18:43:05.1906540Z
2026-05-17T18:43:05.1907940Z 8.1.1 Se você usar qualquer API para obter dados do Google, você reconhece que os dados podem estar protegidos por direitos de propriedade intelectual pertencentes ao Google ou às partes que fornecem os dados (ou a outras pessoas ou empresas em nome delas). O uso de qualquer API desse tipo pode estar sujeito a Termos de Serviço adicionais. Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados (no todo ou em parte), a menos que seja permitido pelos Termos de Serviço relevantes.
2026-05-17T18:43:05.1909403Z
2026-05-17T18:43:05.1911968Z 8.1.2 Se você usar qualquer API para recuperar dados de um usuário do Google, você reconhece e concorda que só poderá recuperar dados com o consentimento explícito do usuário e somente quando, e para os fins limitados para os quais, o usuário lhe concedeu permissão para fazê-lo. Se você usar a API do Serviço de Reconhecimento do Android, documentada no seguinte URL: https://developer.android.com/reference/android/speech/RecognitionService, conforme atualizada periodicamente, você reconhece que o uso da API está sujeito ao Adendo de Processamento de Dados para Produtos nos quais o Google é um Processador de Dados, que pode ser encontrado no seguinte URL: https://privacy.google.com/businesses/gdprprocessorterms/, conforme atualizado periodicamente. Ao clicar em "Aceitar", você concorda com os termos do Adendo de Processamento de Dados para Produtos nos quais o Google é um Processador de Dados.
2026-05-17T18:43:05.1914643Z
2026-05-17T18:43:05.1914650Z
2026-05-17T18:43:05.1914781Z 9. Rescisão do Contrato de Licença
2026-05-17T18:43:05.1915098Z
2026-05-17T18:43:05.1915535Z 9.1 O Contrato de Licença continuará em vigor até ser rescindido por você ou pelo Google, conforme estabelecido abaixo.
2026-05-17T18:43:05.1916113Z
2026-05-17T18:43:05.1916454Z 9.2 Se desejar rescindir o Contrato de Licença, poderá fazê-lo cessando a utilização do SDK e quaisquer credenciais de desenvolvedor relevantes.
2026-05-17T18:43:05.1916871Z
2026-05-17T18:43:05.1918762Z 9.3 O Google poderá, a qualquer momento, rescindir o Contrato de Licença com você se: (A) você violar qualquer disposição do Contrato de Licença; ou (B) o Google for obrigado a fazê-lo por lei; ou (C) o parceiro com quem o Google ofereceu determinadas partes do SDK (como APIs) a você tiver encerrado seu relacionamento com o Google ou deixado de oferecer determinadas partes do SDK a você; ou (D) o Google decidir não fornecer mais o SDK ou determinadas partes do SDK aos usuários no país em que você reside ou de onde você usa o serviço, ou se o fornecimento do SDK ou de determinados serviços do SDK a você pelo Google, a critério exclusivo do Google, deixar de ser comercialmente viável.
2026-05-17T18:43:05.1920778Z
2026-05-17T18:43:05.1922054Z 9.4 Quando o Contrato de Licença chegar ao fim, todos os direitos, obrigações e responsabilidades legais que você e o Google tenham adquirido, estejam sujeitos (ou que tenham se acumulado ao longo do tempo enquanto o Contrato de Licença esteve em vigor) ou que estejam expressamente previstos para continuar indefinidamente, não serão afetados por essa rescisão, e as disposições do parágrafo 14.7 continuarão a se aplicar a tais direitos, obrigações e responsabilidades indefinidamente.
2026-05-17T18:43:05.1923378Z
2026-05-17T18:43:05.1923383Z
2026-05-17T18:43:05.1923465Z 10. ISENÇÃO DE GARANTIAS
2026-05-17T18:43:05.1923610Z
2026-05-17T18:43:05.1924084Z 10.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O USO DO SDK É POR SUA CONTA E RISCO E QUE O SDK É FORNECIDO "NO ESTADO EM QUE SE ENCONTRA" E "CONFORME DISPONÍVEL", SEM GARANTIA DE QUALQUER TIPO POR PARTE DO GOOGLE.
2026-05-17T18:43:05.1924817Z
2026-05-17T18:43:05.1926020Z 10.2 O USO DO SDK E DE QUALQUER MATERIAL BAIXADO OU OBTIDO DE OUTRA FORMA ATRAVÉS DO USO DO SDK É DE SUA INTEIRA RESPONSABILIDADE E RISCO, E VOCÊ É O ÚNICO RESPONSÁVEL POR QUALQUER DANO AO SEU SISTEMA DE COMPUTADOR OU OUTRO DISPOSITIVO OU PERDA DE DADOS QUE RESULTE DE TAL USO.
2026-05-17T18:43:05.1926954Z
2026-05-17T18:43:05.1927672Z 10.3 O GOOGLE EXPRESSAMENTE SE EXIME DE TODAS AS GARANTIAS E CONDIÇÕES DE QUALQUER TIPO, SEJAM ELAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS E CONDIÇÕES IMPLÍCITAS DE COMERCIABILIDADE, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO.
2026-05-17T18:43:05.1928476Z
2026-05-17T18:43:05.1928481Z
2026-05-17T18:43:05.1928560Z 11. LIMITAÇÃO DE RESPONSABILIDADE
2026-05-17T18:43:05.1928702Z
2026-05-17T18:43:05.1929952Z 11.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O GOOGLE, SUAS SUBSIDIÁRIAS E AFILIADAS, E SEUS LICENCIADORES NÃO SERÃO RESPONSÁVEIS PERANTE VOCÊ SOB QUALQUER TEORIA DE RESPONSABILIDADE POR QUAISQUER DANOS DIRETOS, INDIRETOS, INCIDENTAIS, ESPECIAIS, CONSEQUENCIAIS OU EXEMPLARES QUE POSSAM SER INCORRIDOS POR VOCÊ, INCLUINDO QUALQUER PERDA DE DADOS, INDEPENDENTEMENTE DE O GOOGLE OU SEUS REPRESENTANTES TEREM SIDO AVISADOS OU DEVESSEM ESTAR CIENTES DA POSSIBILIDADE DE TAIS PERDAS OCORRER.
2026-05-17T18:43:05.1931408Z
2026-05-17T18:43:05.1931412Z
2026-05-17T18:43:05.1931492Z 12. Indenização
2026-05-17T18:43:05.1931603Z
2026-05-17T18:43:05.1934298Z 12.1 Na máxima extensão permitida por lei, você concorda em defender, indenizar e isentar o Google, suas afiliadas e seus respectivos diretores, executivos, funcionários e agentes de quaisquer reivindicações, ações, processos ou procedimentos, bem como quaisquer perdas, responsabilidades, danos, custos e despesas (incluindo honorários advocatícios razoáveis) decorrentes de ou resultantes de (a) seu uso do SDK, (b) qualquer aplicativo que você desenvolva no SDK que infrinja qualquer direito autoral, marca registrada, segredo comercial, imagem comercial, patente ou outro direito de propriedade intelectual de qualquer pessoa ou difame qualquer pessoa ou viole seus direitos de publicidade ou privacidade, e (c) qualquer descumprimento por você do Contrato de Licença.
2026-05-17T18:43:05.1937206Z
2026-05-17T18:43:05.1937212Z
2026-05-17T18:43:05.1937327Z 13. Alterações ao Contrato de Licença
2026-05-17T18:43:05.1937567Z
2026-05-17T18:43:05.1938669Z 13.1 O Google poderá fazer alterações ao Contrato de Licença ao distribuir novas versões do SDK. Quando essas alterações forem feitas, o Google disponibilizará uma nova versão do Contrato de Licença no site onde o SDK é disponibilizado.
2026-05-17T18:43:05.1939965Z
2026-05-17T18:43:05.1939972Z
2026-05-17T18:43:05.1940087Z 14. Termos Legais Gerais
2026-05-17T18:43:05.1940286Z
2026-05-17T18:43:05.1942130Z 14.1 O Contrato de Licença constitui o acordo legal integral entre você e o Google e rege seu uso do SDK (excluindo quaisquer serviços que o Google possa fornecer a você sob um contrato escrito separado), e substitui completamente quaisquer acordos anteriores entre você e o Google em relação ao SDK.
2026-05-17T18:43:05.1943839Z
2026-05-17T18:43:05.1945488Z 14.2 Você concorda que, se o Google não exercer ou fizer valer qualquer direito ou recurso legal contido no Contrato de Licença (ou do qual o Google se beneficie de acordo com qualquer lei aplicável), isso não será considerado uma renúncia formal dos direitos do Google e que esses direitos ou recursos ainda estarão disponíveis para o Google.
2026-05-17T18:43:05.1947166Z
2026-05-17T18:43:05.1948731Z 14.3 Se qualquer tribunal competente para decidir sobre esta matéria declarar que qualquer disposição do Contrato de Licença é inválida, essa disposição será removida do Contrato de Licença sem afetar o restante do Contrato de Licença. As demais disposições do Contrato de Licença continuarão válidas e em vigor.
2026-05-17T18:43:05.1951250Z
2026-05-17T18:43:05.1953509Z 14.4 Você reconhece e concorda que cada membro do grupo de empresas do qual o Google é a controladora será considerado terceiro beneficiário do Contrato de Licença e que tais outras empresas terão o direito de exigir o cumprimento e se valer diretamente de qualquer disposição do Contrato de Licença que lhes confira um benefício (ou direitos em seu favor). Além disso, nenhuma outra pessoa ou empresa será considerada terceiro beneficiário do Contrato de Licença.
2026-05-17T18:43:05.1955174Z
2026-05-17T18:43:05.1955914Z 14.5 RESTRIÇÕES DE EXPORTAÇÃO. O SDK ESTÁ SUJEITO ÀS LEIS E REGULAMENTOS DE EXPORTAÇÃO DOS ESTADOS UNIDOS. VOCÊ DEVE CUMPRIR TODAS AS LEIS E REGULAMENTOS DE EXPORTAÇÃO NACIONAIS E INTERNACIONAIS APLICÁVEIS AO SDK. ESSAS LEIS INCLUEM RESTRIÇÕES QUANTO A DESTINOS, USUÁRIOS FINAIS E USO FINAL.
2026-05-17T18:43:05.1956732Z
2026-05-17T18:43:05.1957707Z 14.6 Os direitos concedidos no Contrato de Licença não podem ser cedidos ou transferidos por você ou pelo Google sem a prévia aprovação por escrito da outra parte. Nem você nem o Google poderão delegar suas responsabilidades ou obrigações sob o Contrato de Licença sem a prévia aprovação por escrito da outra parte.
2026-05-17T18:43:05.1958742Z
2026-05-17T18:43:05.1960492Z 14.7 O Contrato de Licença e sua relação com o Google sob o Contrato de Licença serão regidos pelas leis do Estado da Califórnia, sem levar em consideração suas disposições sobre conflito de leis. Você e o Google concordam em se submeter à jurisdição exclusiva dos tribunais localizados no condado de Santa Clara, Califórnia, para resolver qualquer questão legal decorrente do Contrato de Licença. Não obstante, você concorda que o Google ainda poderá solicitar medidas cautelares (ou um tipo equivalente de tutela jurisdicional urgente) em qualquer jurisdição.
2026-05-17T18:43:05.1962204Z
2026-05-17T18:43:05.1962209Z
2026-05-17T18:43:05.1962286Z 16 de janeiro de 2019
2026-05-17T18:43:05.1962504Z ---------------------------------------
2026-05-17T18:43:05.1962771Z Aceitar? (s/N):
2026-05-17T18:43:05.1963153Z 4/6: Licença android-sdk-preview-license:
2026-05-17T18:43:05.1963436Z ---------------------------------------
Para começar a usar a versão prévia do SDK do Android, você deve concordar com os seguintes termos e condições. Conforme descrito abaixo, observe que esta é uma versão prévia do SDK do Android, sujeita a alterações, e que você a utiliza por sua conta e risco. A versão prévia do SDK do Android não é uma versão estável e pode conter erros e defeitos que podem causar sérios danos aos seus sistemas de computador, dispositivos e dados.
2026-05-17T18:43:05.1965855Z
2026-05-17T18:43:05.1966034Z Este é o Contrato de Licença de Pré-visualização do SDK do Android (o "Contrato de Licença").
2026-05-17T18:43:05.1966293Z
2026-05-17T18:43:05.1966374Z 1. Introdução
2026-05-17T18:43:05.1966487Z
2026-05-17T18:43:05.1968070Z 1.1 O SDK de pré-visualização do Android (referido no Contrato de Licença como "Pré-visualização" e incluindo especificamente os arquivos do sistema Android, APIs empacotadas e arquivos da biblioteca de pré-visualização, se e quando forem disponibilizados) é licenciado para você sujeito aos termos do Contrato de Licença. O Contrato de Licença constitui um contrato juridicamente vinculativo entre você e o Google em relação ao seu uso da Pré-visualização.
2026-05-17T18:43:05.1969290Z
2026-05-17T18:43:05.1969876Z 1.2 "Android" significa a pilha de software Android para dispositivos, disponibilizada pelo Projeto de Código Aberto do Android, que está localizado no seguinte URL: http://source.android.com/, e que é atualizada periodicamente.
2026-05-17T18:43:05.1970748Z
2026-05-17T18:43:05.1971168Z 1.3 "Google" significa Google Inc., uma corporação de Delaware com sede principal em 1600 Amphitheatre Parkway, Mountain View, CA 94043, Estados Unidos.
2026-05-17T18:43:05.1971665Z
2026-05-17T18:43:05.1971759Z 2. Aceitação do Contrato de Licença
2026-05-17T18:43:05.1971912Z
2026-05-17T18:43:05.1972290Z 2.1 Para usar a versão de pré-visualização, você precisa primeiro aceitar o Contrato de Licença. Você não poderá usar a versão de pré-visualização se não aceitar o Contrato de Licença.
2026-05-17T18:43:05.1972755Z
2026-05-17T18:43:05.1973013Z 2.2 Ao clicar em aceitar e/ou usar a Pré-visualização, você concorda com os termos do Contrato de Licença.
2026-05-17T18:43:05.1973349Z
2026-05-17T18:43:05.1974055Z 2.3 Você não poderá usar a Pré-visualização nem aceitar o Contrato de Licença se for uma pessoa impedida de receber a Pré-visualização pelas leis dos Estados Unidos ou de outros países, incluindo o país em que você reside ou de onde você usa a Pré-visualização.
2026-05-17T18:43:05.1974846Z
2026-05-17T18:43:05.1976083Z 2.4 Se você for usar a versão de pré-visualização internamente em sua empresa ou organização, você concorda em se vincular ao Contrato de Licença em nome de seu empregador ou outra entidade, e declara e garante que possui plena autoridade legal para vincular seu empregador ou tal entidade ao Contrato de Licença. Caso não possua a autoridade necessária, você não poderá aceitar o Contrato de Licença nem usar a versão de pré-visualização em nome de seu empregador ou outra entidade.
2026-05-17T18:43:05.1977398Z
2026-05-17T18:43:05.1977482Z 3. Pré-visualização da licença do Google
2026-05-17T18:43:05.1977629Z
2026-05-17T18:43:05.1978532Z 3.1 Sujeito aos termos do Contrato de Licença, o Google concede a você uma licença gratuita, não atribuível, não exclusiva, não sublicenciável, limitada e revogável para usar a versão de pré-visualização, pessoalmente ou internamente em sua empresa ou organização, exclusivamente para desenvolver aplicativos para serem executados na plataforma Android.
2026-05-17T18:43:05.1979497Z
2026-05-17T18:43:05.1980791Z 3.2 Você concorda que o Google ou terceiros detêm todos os direitos legais, títulos e interesses relativos à Prévia, incluindo quaisquer Direitos de Propriedade Intelectual que subsistam na Prévia. "Direitos de Propriedade Intelectual" significa todos e quaisquer direitos sob a lei de patentes, lei de direitos autorais, lei de segredos comerciais, lei de marcas registradas e quaisquer outros direitos de propriedade. O Google reserva-se todos os direitos não expressamente concedidos a você.
2026-05-17T18:43:05.1982010Z
2026-05-17T18:43:05.1983716Z 3.3 Você não pode usar a Pré-visualização para qualquer finalidade que não seja expressamente permitida pelo Contrato de Licença. Exceto na medida exigida por licenças de terceiros aplicáveis, você não pode: (a) copiar (exceto para fins de backup), modificar, adaptar, redistribuir, descompilar, fazer engenharia reversa, desmontar ou criar trabalhos derivados da Pré-visualização ou de qualquer parte da Pré-visualização; ou (b) carregar qualquer parte da Pré-visualização em um aparelho celular ou qualquer outro dispositivo de hardware, exceto um computador pessoal, combinar qualquer parte da Pré-visualização com outro software ou distribuir qualquer software ou dispositivo que incorpore uma parte da Pré-visualização.
2026-05-17T18:43:05.1985586Z
2026-05-17T18:43:05.1986290Z 3.4 Você concorda que não tomará nenhuma ação que possa causar ou resultar na fragmentação do Android, incluindo, entre outras, a distribuição, participação na criação ou promoção de qualquer forma de um kit de desenvolvimento de software derivado da versão de pré-visualização.
2026-05-17T18:43:05.1987083Z
2026-05-17T18:43:05.1988347Z 3.5 O uso, a reprodução e a distribuição de componentes da versão de pré-visualização licenciados sob uma licença de software de código aberto são regidos exclusivamente pelos termos dessa licença de software de código aberto e não pelo Contrato de Licença. Você concorda em permanecer um licenciado em situação regular em relação a essas licenças de software de código aberto, sob todos os direitos concedidos, e em se abster de quaisquer ações que possam rescindir, suspender ou violar tais direitos.
2026-05-17T18:43:05.1989632Z
2026-05-17T18:43:05.1991024Z 3.6 Você concorda que a forma e a natureza da Pré-visualização fornecida pelo Google podem ser alteradas sem aviso prévio e que versões futuras da Pré-visualização podem ser incompatíveis com aplicativos desenvolvidos em versões anteriores da Pré-visualização. Você concorda que o Google pode interromper (permanentemente ou temporariamente) o fornecimento da Pré-visualização (ou quaisquer recursos dentro da Pré-visualização) para você ou para os usuários em geral, a critério exclusivo do Google, sem aviso prévio.
2026-05-17T18:43:05.1992367Z
2026-05-17T18:43:05.1992818Z 3.7 Nada no Contrato de Licença lhe dá o direito de usar quaisquer nomes comerciais, marcas registradas, marcas de serviço, logotipos, nomes de domínio ou outras características distintivas da marca do Google.
2026-05-17T18:43:05.1993350Z
2026-05-17T18:43:05.1993872Z 3.8 Você concorda em não remover, ocultar ou alterar quaisquer avisos de direitos de propriedade (incluindo avisos de direitos autorais e marcas registradas) que possam estar afixados ou contidos na Pré-visualização.
2026-05-17T18:43:05.1994463Z
2026-05-17T18:43:05.1994542Z 4. Uso da Pré-visualização por Você
2026-05-17T18:43:05.1994682Z
2026-05-17T18:43:05.1995530Z 4.1 O Google concorda que nada no Contrato de Licença confere ao Google qualquer direito, título ou interesse seu (ou de seus licenciadores) sob o Contrato de Licença em relação a quaisquer aplicativos de software que você desenvolva usando a Prévia, incluindo quaisquer direitos de propriedade intelectual que existam nesses aplicativos.
2026-05-17T18:43:05.1996459Z
2026-05-17T18:43:05.1997487Z 4.2 Você concorda em usar a Pré-visualização e escrever aplicativos apenas para fins permitidos por (a) o Contrato de Licença e (b) qualquer lei, regulamento ou práticas ou diretrizes geralmente aceitas aplicáveis ​​nas jurisdições relevantes (incluindo quaisquer leis relativas à exportação de dados ou software de e para os Estados Unidos ou outros países relevantes).
2026-05-17T18:43:05.1998579Z
2026-05-17T18:43:05.2000911Z 4.3 Você concorda que, se usar a versão de pré-visualização para desenvolver aplicativos, protegerá a privacidade e os direitos legais dos usuários. Se os usuários fornecerem nomes de usuário, senhas ou outras informações de login ou informações pessoais, você deverá informá-los de que essas informações estarão disponíveis para o seu aplicativo e deverá fornecer um aviso de privacidade e proteção legalmente adequados para esses usuários. Se o seu aplicativo armazenar informações pessoais ou confidenciais fornecidas pelos usuários, deverá fazê-lo de forma segura. Se os usuários fornecerem informações da Conta do Google, seu aplicativo poderá usar essas informações somente para acessar a Conta do Google do usuário quando e para os fins limitados para os quais cada usuário lhe concedeu permissão para fazê-lo.
2026-05-17T18:43:05.2003103Z
2026-05-17T18:43:05.2003940Z 4.4 Você concorda que não se envolverá em nenhuma atividade com a Prévia, incluindo o desenvolvimento ou distribuição de um aplicativo, que interfira, interrompa, danifique ou acesse de forma não autorizada os servidores, redes ou outras propriedades ou serviços do Google ou de terceiros.
2026-05-17T18:43:05.2004914Z
2026-05-17T18:43:05.2005886Z 4.5 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) quaisquer dados, conteúdo ou recursos que você criar, transmitir ou exibir por meio do Android e/ou aplicativos para Android, e pelas consequências de suas ações (incluindo qualquer perda ou dano que o Google possa sofrer) ao fazê-lo.
2026-05-17T18:43:05.2006936Z
2026-05-17T18:43:05.2008036Z 4.6 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) qualquer violação de suas obrigações sob o Contrato de Licença, qualquer contrato de terceiros aplicável ou Termos de Serviço, ou qualquer lei ou regulamento aplicável, e pelas consequências (incluindo qualquer perda ou dano que o Google ou terceiros possam sofrer) de tal violação.
2026-05-17T18:43:05.2009224Z
2026-05-17T18:43:05.2010835Z 4.7 A versão de pré-visualização está em desenvolvimento, e seus testes e feedback são uma parte importante do processo de desenvolvimento. Ao usar a versão de pré-visualização, você reconhece que a implementação de alguns recursos ainda está em desenvolvimento e que você não deve confiar que a versão de pré-visualização terá todas as funcionalidades de uma versão estável. Você concorda em não distribuir ou publicar nenhum aplicativo usando esta versão de pré-visualização, pois ela não terá mais suporte após o lançamento do SDK oficial do Android.
2026-05-17T18:43:05.2012302Z
2026-05-17T18:43:05.2012388Z 5. Suas credenciais de desenvolvedor
2026-05-17T18:43:05.2012529Z
2026-05-17T18:43:05.2013329Z 5.1 Você concorda que é responsável por manter a confidencialidade de quaisquer credenciais de desenvolvedor que possam ser emitidas para você pelo Google ou que você possa escolher, e que será o único responsável por todos os aplicativos desenvolvidos com suas credenciais de desenvolvedor.
2026-05-17T18:43:05.2014206Z
2026-05-17T18:43:05.2014286Z 6. Privacidade e Informações
2026-05-17T18:43:05.2014426Z
2026-05-17T18:43:05.2015844Z 6.1 Para inovar e aprimorar continuamente o Preview, o Google poderá coletar determinadas estatísticas de uso do software, incluindo, entre outras, um identificador exclusivo, o endereço IP associado, o número da versão do software e informações sobre quais ferramentas e/ou serviços do Preview estão sendo usados ​​e como estão sendo usados. Antes que qualquer uma dessas informações seja coletada, o Preview notificará você e solicitará seu consentimento. Caso você negue o consentimento, as informações não serão coletadas.
2026-05-17T18:43:05.2017335Z
2026-05-17T18:43:05.2017856Z 6.2 Os dados coletados são examinados de forma agregada para melhorar a Pré-visualização e são mantidos de acordo com a Política de Privacidade do Google, localizada em http://www.google.com/policies/privacy/.
2026-05-17T18:43:05.2018447Z
2026-05-17T18:43:05.2018540Z 7. Aplicativos de terceiros
2026-05-17T18:43:05.2018675Z
2026-05-17T18:43:05.2020475Z 7.1 Se você usar o Preview para executar aplicativos desenvolvidos por terceiros ou que acessem dados, conteúdo ou recursos fornecidos por terceiros, você concorda que o Google não é responsável por esses aplicativos, dados, conteúdo ou recursos. Você entende que todos os dados, conteúdo ou recursos aos quais você possa acessar por meio desses aplicativos de terceiros são de responsabilidade exclusiva da pessoa que os originou e que o Google não é responsável por qualquer perda ou dano que você possa sofrer como resultado do uso ou acesso a quaisquer desses aplicativos, dados, conteúdo ou recursos de terceiros.
2026-05-17T18:43:05.2022333Z
2026-05-17T18:43:05.2023697Z 7.2 Você deve estar ciente de que os dados, o conteúdo e os recursos apresentados a você por meio de um aplicativo de terceiros podem estar protegidos por direitos de propriedade intelectual pertencentes aos provedores (ou a outras pessoas ou empresas em seu nome). Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados, conteúdo ou recursos (no todo ou em parte), a menos que tenha recebido permissão expressa dos respectivos proprietários.
2026-05-17T18:43:05.2025225Z
2026-05-17T18:43:05.2025672Z 7.3 Você reconhece que o seu uso de tais aplicativos, dados, conteúdo ou recursos de terceiros pode estar sujeito a termos separados entre você e o terceiro relevante.
2026-05-17T18:43:05.2026203Z
2026-05-17T18:43:05.2026274Z 8. Usando APIs do Google
2026-05-17T18:43:05.2026396Z
2026-05-17T18:43:05.2026466Z 8.1 APIs do Google
2026-05-17T18:43:05.2026573Z
2026-05-17T18:43:05.2027962Z 8.1.1 Se você usar qualquer API para obter dados do Google, você reconhece que os dados podem estar protegidos por direitos de propriedade intelectual pertencentes ao Google ou às partes que fornecem os dados (ou a outras pessoas ou empresas em nome delas). O uso de qualquer API desse tipo pode estar sujeito a Termos de Serviço adicionais. Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados (no todo ou em parte), a menos que seja permitido pelos Termos de Serviço relevantes.
2026-05-17T18:43:05.2029440Z
2026-05-17T18:43:05.2030182Z 8.1.2 Se você usar qualquer API para recuperar dados de um usuário do Google, você reconhece e concorda que só poderá recuperar dados com o consentimento explícito do usuário e somente quando, e para os fins limitados para os quais, o usuário lhe deu permissão para fazê-lo.
2026-05-17T18:43:05.2031076Z
2026-05-17T18:43:05.2031172Z 9. Rescisão do Contrato de Licença
2026-05-17T18:43:05.2031328Z
2026-05-17T18:43:05.2031594Z 9.1 O Contrato de Licença continuará em vigor até ser rescindido por você ou pelo Google, conforme estabelecido abaixo.
2026-05-17T18:43:05.2031950Z
2026-05-17T18:43:05.2032291Z 9.2 Se desejar rescindir o Contrato de Licença, poderá fazê-lo cessando a utilização da versão de pré-visualização e quaisquer credenciais de desenvolvedor relevantes.
2026-05-17T18:43:05.2032711Z
2026-05-17T18:43:05.2032969Z 9.3 O Google poderá, a qualquer momento, rescindir o Contrato de Licença, com ou sem justa causa, mediante notificação a você.
2026-05-17T18:43:05.2033302Z
2026-05-17T18:43:05.2034218Z 9.4 O Contrato de Licença será rescindido automaticamente sem aviso prévio ou outra ação na data que ocorrer primeiro entre: (A) quando o Google deixar de fornecer a Prévia ou certas partes da Prévia aos usuários no país em que você reside ou de onde você usa o serviço; e (B) o Google lançar uma versão final do SDK do Android.
2026-05-17T18:43:05.2035212Z
2026-05-17T18:43:05.2035871Z 9.5 Quando o Contrato de Licença for rescindido, a licença concedida a você no Contrato de Licença será rescindida, você deverá cessar imediatamente todo o uso da Pré-visualização e as disposições dos parágrafos 10, 11, 12 e 14 permanecerão em vigor indefinidamente.
2026-05-17T18:43:05.2036607Z
2026-05-17T18:43:05.2036674Z 10. AVISOS LEGAIS
2026-05-17T18:43:05.2036776Z
2026-05-17T18:43:05.2037275Z 10.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O USO DA PRÉ-VISUALIZAÇÃO É POR SUA CONTA E RISCO E QUE A PRÉ-VISUALIZAÇÃO É FORNECIDA "NO ESTADO EM QUE SE ENCONTRA" E "CONFORME DISPONÍVEL", SEM QUALQUER GARANTIA DO GOOGLE.
2026-05-17T18:43:05.2037842Z
2026-05-17T18:43:05.2039437Z 10.2 O USO DA PRÉVIA E DE QUALQUER MATERIAL BAIXADO OU OBTIDO DE OUTRA FORMA ATRAVÉS DO USO DA PRÉVIA É DE SUA INTEIRA RESPONSABILIDADE E RISCO, E VOCÊ É O ÚNICO RESPONSÁVEL POR QUALQUER DANO AO SEU SISTEMA DE COMPUTADOR OU OUTRO DISPOSITIVO OU PERDA DE DADOS RESULTANTE DE TAL USO. SEM LIMITAR O ACIMA EXPOSTO, VOCÊ ENTENDE QUE A PRÉVIA NÃO É UMA VERSÃO ESTÁVEL E PODE CONTER ERROS, DEFEITOS E VULNERABILIDADES DE SEGURANÇA QUE PODEM RESULTAR EM DANOS SIGNIFICATIVOS, INCLUINDO A PERDA COMPLETA E IRRECUPERÁVEL DO USO DO SEU SISTEMA DE COMPUTADOR OU OUTRO DISPOSITIVO.
2026-05-17T18:43:05.2041219Z
2026-05-17T18:43:05.2041926Z 10.3 O GOOGLE EXPRESSAMENTE SE EXIME DE TODAS AS GARANTIAS E CONDIÇÕES DE QUALQUER TIPO, SEJAM ELAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS E CONDIÇÕES IMPLÍCITAS DE COMERCIABILIDADE, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO.
2026-05-17T18:43:05.2042729Z
2026-05-17T18:43:05.2042807Z 11. LIMITAÇÃO DE RESPONSABILIDADE
2026-05-17T18:43:05.2042938Z
2026-05-17T18:43:05.2044189Z 11.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O GOOGLE, SUAS SUBSIDIÁRIAS E AFILIADAS, E SEUS LICENCIADORES NÃO SERÃO RESPONSÁVEIS PERANTE VOCÊ SOB QUALQUER TEORIA DE RESPONSABILIDADE POR QUAISQUER DANOS DIRETOS, INDIRETOS, INCIDENTAIS, ESPECIAIS, CONSEQUENCIAIS OU EXEMPLARES QUE POSSAM SER INCORRIDOS POR VOCÊ, INCLUINDO QUALQUER PERDA DE DADOS, INDEPENDENTEMENTE DE O GOOGLE OU SEUS REPRESENTANTES TEREM SIDO AVISADOS OU DEVESSEM ESTAR CIENTES DA POSSIBILIDADE DE TAIS PERDAS OCORRER.
2026-05-17T18:43:05.2045603Z
2026-05-17T18:43:05.2045673Z 12. Indenização
2026-05-17T18:43:05.2045788Z
2026-05-17T18:43:05.2048220Z 12.1 Na máxima extensão permitida por lei, você concorda em defender, indenizar e isentar o Google, suas afiliadas e seus respectivos diretores, executivos, funcionários e agentes de quaisquer reivindicações, ações, processos ou procedimentos, bem como quaisquer perdas, responsabilidades, danos, custos e despesas (incluindo honorários advocatícios razoáveis) decorrentes de ou resultantes de (a) seu uso da Prévia, (b) qualquer aplicativo que você desenvolva na Prévia que infrinja quaisquer Direitos de Propriedade Intelectual de qualquer pessoa ou difame qualquer pessoa ou viole seus direitos de publicidade ou privacidade e (c) qualquer descumprimento por você do Contrato de Licença.
2026-05-17T18:43:05.2050199Z
2026-05-17T18:43:05.2050283Z 13. Alterações ao Contrato de Licença
2026-05-17T18:43:05.2050555Z
2026-05-17T18:43:05.2051231Z 13.1 O Google poderá fazer alterações ao Contrato de Licença ao distribuir novas versões da Prévia. Quando essas alterações forem feitas, o Google disponibilizará uma nova versão do Contrato de Licença no site onde a Prévia estiver disponível.
2026-05-17T18:43:05.2051975Z
2026-05-17T18:43:05.2052047Z 14. Termos Legais Gerais
2026-05-17T18:43:05.2052174Z
2026-05-17T18:43:05.2053059Z 14.1 O Contrato de Licença constitui o acordo legal integral entre você e o Google e rege seu uso da Prévia (excluindo quaisquer serviços que o Google possa fornecer a você sob um contrato escrito separado), e substitui completamente quaisquer acordos anteriores entre você e o Google em relação à Prévia.
2026-05-17T18:43:05.2054046Z
2026-05-17T18:43:05.2054922Z 14.2 Você concorda que, se o Google não exercer ou fizer valer qualquer direito ou recurso legal contido no Contrato de Licença (ou do qual o Google se beneficie de acordo com qualquer lei aplicável), isso não será considerado uma renúncia formal dos direitos do Google e que esses direitos ou recursos ainda estarão disponíveis para o Google.
2026-05-17T18:43:05.2055876Z
2026-05-17T18:43:05.2056846Z 14.3 Se qualquer tribunal competente para decidir sobre esta matéria considerar que alguma disposição do Contrato de Licença é inválida, essa disposição será removida do Contrato de Licença sem afetar o restante do Contrato de Licença. As demais disposições do Contrato de Licença continuarão válidas e em pleno vigor.
2026-05-17T18:43:05.2057886Z
2026-05-17T18:43:05.2059147Z 14.4 Você reconhece e concorda que cada membro do grupo de empresas do qual o Google é a controladora será considerado terceiro beneficiário do Contrato de Licença e que tais outras empresas terão o direito de exigir o cumprimento e se valer diretamente de qualquer disposição do Contrato de Licença que lhes confira um benefício (ou direitos em seu favor). Além disso, nenhuma outra pessoa ou empresa será considerada terceiro beneficiário do Contrato de Licença.
2026-05-17T18:43:05.2060612Z
2026-05-17T18:43:05.2061399Z 14.5 RESTRIÇÕES DE EXPORTAÇÃO. A PRÉVIA ESTÁ SUJEITA ÀS LEIS E REGULAMENTOS DE EXPORTAÇÃO DOS ESTADOS UNIDOS. VOCÊ DEVE CUMPRIR TODAS AS LEIS E REGULAMENTOS DE EXPORTAÇÃO NACIONAIS E INTERNACIONAIS APLICÁVEIS À PRÉVIA. ESSAS LEIS INCLUEM RESTRIÇÕES QUANTO A DESTINOS, USUÁRIOS FINAIS E USO FINAL.
2026-05-17T18:43:05.2062255Z
2026-05-17T18:43:05.2063144Z 14.6 O Contrato de Licença não pode ser cedido ou transferido por você sem a prévia aprovação por escrito do Google, e qualquer tentativa de cessão sem tal aprovação será nula. Você não poderá delegar suas responsabilidades ou obrigações sob o Contrato de Licença sem a prévia aprovação por escrito do Google.
2026-05-17T18:43:05.2064200Z
2026-05-17T18:43:05.2065805Z 14.7 O Contrato de Licença e sua relação com o Google sob o Contrato de Licença serão regidos pelas leis do Estado da Califórnia, sem levar em consideração suas disposições sobre conflito de leis. Você e o Google concordam em se submeter à jurisdição exclusiva dos tribunais localizados no condado de Santa Clara, Califórnia, para resolver qualquer questão legal decorrente do Contrato de Licença. Não obstante, você concorda que o Google ainda poderá solicitar medidas cautelares (ou um tipo equivalente de tutela jurisdicional urgente) em qualquer jurisdição.
2026-05-17T18:43:05.2067488Z
2026-05-17T18:43:05.2067553Z Junho de 2014.
2026-05-17T18:43:05.2067730Z ---------------------------------------
2026-05-17T18:43:05.2067952Z Aceitar? (s/N):
2026-05-17T18:43:05.2068146Z 5/6: Licença google-gdk-license:
2026-05-17T18:43:05.2068363Z ---------------------------------------
2026-05-17T18:43:05.2068661Z Esta é uma versão de pré-visualização para desenvolvedores do GDK, sujeita a alterações.
2026-05-17T18:43:05.2068893Z
2026-05-17T18:43:05.2068964Z Termos e Condições
2026-05-17T18:43:05.2069083Z
2026-05-17T18:43:05.2069253Z Este é o Contrato de Licença do Kit de Desenvolvimento Glass.
2026-05-17T18:43:05.2069447Z
2026-05-17T18:43:05.2069524Z 1. Introdução
2026-05-17T18:43:05.2069622Z
2026-05-17T18:43:05.2070834Z 1.1 O Glass Development Kit (referido neste Contrato de Licença como "GDK" e incluindo especificamente os arquivos do sistema Android, APIs empacotadas e arquivos de biblioteca GDK, se e quando forem disponibilizados) é licenciado para você sujeito aos termos deste Contrato de Licença. Este Contrato de Licença constitui um contrato juridicamente vinculativo entre você e o Google em relação ao seu uso do GDK.
2026-05-17T18:43:05.2072016Z
2026-05-17T18:43:05.2072212Z 1.2 "Glass" significa dispositivos Glass e o conjunto de software Glass para uso em dispositivos Glass.
2026-05-17T18:43:05.2072500Z
2026-05-17T18:43:05.2072504Z
2026-05-17T18:43:05.2073090Z 1.3 "Android" significa a pilha de software Android para dispositivos, disponibilizada pelo Projeto de Código Aberto do Android, que está localizado no seguinte URL: http://source.android.com/, e que é atualizada periodicamente.
2026-05-17T18:43:05.2073745Z
2026-05-17T18:43:05.2074158Z 1.4 "Google" significa Google Inc., uma corporação de Delaware com sede principal em 1600 Amphitheatre Parkway, Mountain View, CA 94043, Estados Unidos.
2026-05-17T18:43:05.2074659Z
2026-05-17T18:43:05.2074745Z 2. Aceitação deste Contrato de Licença
2026-05-17T18:43:05.2074898Z
2026-05-17T18:43:05.2075255Z 2.1 Para usar o GDK, você deve primeiro concordar com este Contrato de Licença. Você não poderá usar o GDK se não aceitar este Contrato de Licença.
2026-05-17T18:43:05.2075683Z
2026-05-17T18:43:05.2075873Z 2.2 Ao clicar em aceitar, você concorda com os termos deste Contrato de Licença.
2026-05-17T18:43:05.2076149Z
2026-05-17T18:43:05.2076816Z 2.3 Você não poderá usar o GDK nem aceitar o Contrato de Licença se for uma pessoa impedida de receber o GDK pelas leis dos Estados Unidos ou de outros países, incluindo o país em que você reside ou de onde você usa o GDK.
2026-05-17T18:43:05.2077562Z
2026-05-17T18:43:05.2078591Z 2.4 Se você concordar em se vincular a este Contrato de Licença em nome de seu empregador ou outra entidade, você declara e garante que possui plena autoridade legal para vincular seu empregador ou tal entidade a este Contrato de Licença. Caso não possua a autoridade necessária, você não poderá aceitar o Contrato de Licença nem usar o GDK em nome de seu empregador ou outra entidade.
2026-05-17T18:43:05.2079689Z
2026-05-17T18:43:05.2079773Z 3. Licença GDK do Google
2026-05-17T18:43:05.2079902Z
2026-05-17T18:43:05.2080670Z 3.1 Sujeito aos termos deste Contrato de Licença, o Google concede a você uma licença limitada, mundial, isenta de royalties, não transferível e não exclusiva para usar o GDK exclusivamente para desenvolver aplicativos para serem executados na plataforma Glass para dispositivos Glass.
2026-05-17T18:43:05.2081427Z
2026-05-17T18:43:05.2082524Z 3.2 Você concorda que o Google ou terceiros detêm todos os direitos legais, títulos e interesses relativos ao GDK, incluindo quaisquer Direitos de Propriedade Intelectual que subsistam no GDK. "Direitos de Propriedade Intelectual" significa todos e quaisquer direitos sob a lei de patentes, lei de direitos autorais, lei de segredos comerciais, lei de marcas registradas e quaisquer outros direitos de propriedade. O Google reserva-se todos os direitos não expressamente concedidos a você.
2026-05-17T18:43:05.2083788Z
2026-05-17T18:43:05.2085539Z 3.3 Você não pode usar o GDK para qualquer finalidade que não seja expressamente permitida por este Contrato de Licença. Exceto na medida exigida por licenças de terceiros aplicáveis, você não pode: (a) copiar (exceto para fins de backup), modificar, adaptar, redistribuir, descompilar, fazer engenharia reversa, desmontar ou criar trabalhos derivados do GDK ou de qualquer parte do GDK; ou (b) carregar qualquer parte do GDK em um celular, dispositivo vestível ou qualquer outro dispositivo de hardware, exceto um computador pessoal com dispositivo Glass, combinar qualquer parte do GDK com outro software ou distribuir qualquer software ou dispositivo que incorpore uma parte do GDK.
2026-05-17T18:43:05.2087364Z
2026-05-17T18:43:05.2088109Z 3.4 Você concorda que não tomará nenhuma ação que possa causar ou resultar na fragmentação do Glass, incluindo, entre outras, a distribuição, participação na criação ou promoção de qualquer forma de um kit de desenvolvimento de software derivado do GDK.
2026-05-17T18:43:05.2088881Z
2026-05-17T18:43:05.2089460Z 3.5 O uso, a reprodução e a distribuição de componentes do GDK licenciados sob uma licença de software de código aberto são regidos exclusivamente pelos termos dessa licença de software de código aberto e não por este Contrato de Licença.
2026-05-17T18:43:05.2090108Z
2026-05-17T18:43:05.2091472Z 3.6 Você concorda que a forma e a natureza do GDK fornecido pelo Google podem mudar sem aviso prévio e que versões futuras do GDK podem ser incompatíveis com aplicativos desenvolvidos em versões anteriores do GDK. Você concorda que o Google pode interromper (permanentemente ou temporariamente) o fornecimento do GDK (ou quaisquer recursos dentro do GDK) para você ou para os usuários em geral, a critério exclusivo do Google, sem aviso prévio.
2026-05-17T18:43:05.2092746Z
2026-05-17T18:43:05.2093202Z 3.7 Nada neste Contrato de Licença lhe dá o direito de usar quaisquer nomes comerciais, marcas registradas, marcas de serviço, logotipos, nomes de domínio ou outras características distintivas da marca do Google.
2026-05-17T18:43:05.2093741Z
2026-05-17T18:43:05.2094232Z 3.8 Você concorda que não removerá, ocultará ou alterará quaisquer avisos de direitos de propriedade (incluindo avisos de direitos autorais e marcas registradas) que possam estar afixados ou contidos no GDK.
2026-05-17T18:43:05.2094811Z
2026-05-17T18:43:05.2094815Z
2026-05-17T18:43:05.2095842Z 3.9 O uso de quaisquer arquivos de sistema Android, APIs empacotadas ou outros componentes do GDK que fazem parte do Kit de Desenvolvimento de Software Android está sujeito aos termos do Contrato de Licença do Kit de Desenvolvimento de Software Android, localizado em http://developer.android.com/sdk/terms.html. Esses termos são incorporados por referência a este Contrato de Licença.
2026-05-17T18:43:05.2096942Z
2026-05-17T18:43:05.2097014Z 4. Uso do GDK por você
2026-05-17T18:43:05.2097153Z
2026-05-17T18:43:05.2097890Z 4.1 O Google concorda que não obtém nenhum direito, título ou interesse seu (ou de seus licenciadores) sob este Contrato de Licença em relação a quaisquer aplicativos de software que você desenvolva usando o GDK, incluindo quaisquer direitos de propriedade intelectual que existam nesses aplicativos.
2026-05-17T18:43:05.2098704Z
2026-05-17T18:43:05.2100229Z 4.2 Você concorda em usar o GDK e escrever aplicativos apenas para fins permitidos por (a) este Contrato de Licença, (b) as Políticas do Desenvolvedor da Plataforma Glass (localizadas em https://developers.google.com/glass/policies e incorporadas a este Contrato de Licença por referência) e (c) qualquer lei, regulamento ou práticas ou diretrizes geralmente aceitas aplicáveis ​​nas jurisdições relevantes (incluindo quaisquer leis relativas à exportação de dados ou software de e para os Estados Unidos ou outros países relevantes).
2026-05-17T18:43:05.2101965Z
2026-05-17T18:43:05.2104244Z 4.3 Você concorda que, se usar o GDK para desenvolver aplicativos para usuários do público em geral, protegerá a privacidade e os direitos legais desses usuários. Se os usuários fornecerem nomes de usuário, senhas ou outras informações de login ou informações pessoais, você deverá informá-los de que essas informações estarão disponíveis para o seu aplicativo e deverá fornecer um aviso de privacidade e proteção legalmente adequados para esses usuários. Se o seu aplicativo armazenar informações pessoais ou confidenciais fornecidas pelos usuários, deverá fazê-lo de forma segura. Se o usuário fornecer ao seu aplicativo informações da Conta do Google, o seu aplicativo poderá usar essas informações somente para acessar a Conta do Google do usuário quando e para os fins limitados para os quais o usuário lhe tiver dado permissão para fazê-lo.
2026-05-17T18:43:05.2106655Z
2026-05-17T18:43:05.2107555Z 4.4 Você concorda que não se envolverá em nenhuma atividade com o GDK, incluindo o desenvolvimento ou distribuição de um aplicativo, que interfira, interrompa, danifique ou acesse de forma não autorizada os servidores, redes ou outras propriedades ou serviços de terceiros, incluindo, entre outros, o Google.
2026-05-17T18:43:05.2108532Z
2026-05-17T18:43:05.2109544Z 4.5 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) quaisquer dados, conteúdo ou recursos que você criar, transmitir ou exibir através do Glass e/ou aplicativos para Glass, e pelas consequências de suas ações (incluindo qualquer perda ou dano que o Google possa sofrer) ao fazê-lo.
2026-05-17T18:43:05.2110709Z
2026-05-17T18:43:05.2111814Z 4.6 Você concorda que é o único responsável por (e que o Google não tem qualquer responsabilidade perante você ou terceiros por) qualquer violação de suas obrigações sob este Contrato de Licença, qualquer contrato de terceiros aplicável ou Termos de Serviço, ou qualquer lei ou regulamento aplicável, e pelas consequências (incluindo qualquer perda ou dano que o Google ou terceiros possam sofrer) de tal violação.
2026-05-17T18:43:05.2113004Z
2026-05-17T18:43:05.2113009Z
2026-05-17T18:43:05.2114080Z 4.7 O GDK está em desenvolvimento, e seus testes e feedback são uma parte importante do processo de desenvolvimento. Ao usar o GDK, você reconhece que a implementação de alguns recursos ainda está em desenvolvimento e que você não deve confiar que o GDK, os dispositivos Glass, o software do sistema Glass, a API Google Mirror ou os serviços Glass terão todas as funcionalidades de uma versão estável.
2026-05-17T18:43:05.2115202Z
2026-05-17T18:43:05.2115288Z 5. Suas credenciais de desenvolvedor
2026-05-17T18:43:05.2115431Z
2026-05-17T18:43:05.2116226Z 5.1 Você concorda que é responsável por manter a confidencialidade de quaisquer credenciais de desenvolvedor que possam ser emitidas para você pelo Google ou que você mesmo escolha, e que será o único responsável por todos os aplicativos desenvolvidos com suas credenciais de desenvolvedor.
2026-05-17T18:43:05.2117094Z
2026-05-17T18:43:05.2117184Z 6. Privacidade e Informações
2026-05-17T18:43:05.2117314Z
2026-05-17T18:43:05.2117319Z
2026-05-17T18:43:05.2118686Z 6.1 Para inovar e aprimorar continuamente o GDK, o Google pode coletar certas estatísticas de uso do software, incluindo, entre outras, um identificador exclusivo, o endereço IP associado, o número da versão do software e informações sobre quais ferramentas e/ou serviços do GDK estão sendo usados ​​e como estão sendo usados. Antes que qualquer uma dessas informações seja coletada, o GDK notificará você e solicitará seu consentimento. Caso você negue o consentimento, as informações não serão coletadas.
2026-05-17T18:43:05.2120139Z
2026-05-17T18:43:05.2120598Z 6.2 Os dados coletados são examinados de forma agregada para melhorar o GDK e são mantidos de acordo com a Política de Privacidade do Google.
2026-05-17T18:43:05.2121028Z
2026-05-17T18:43:05.2121110Z 7. Aplicativos de terceiros
2026-05-17T18:43:05.2121245Z
2026-05-17T18:43:05.2122934Z 7.1 Se você usar o GDK para executar aplicativos desenvolvidos por terceiros ou que acessem dados, conteúdo ou recursos fornecidos por terceiros, você concorda que o Google não é responsável por esses aplicativos, dados, conteúdo ou recursos. Você entende que todos os dados, conteúdo ou recursos aos quais você possa acessar por meio desses aplicativos de terceiros são de responsabilidade exclusiva da pessoa que os originou e que o Google não é responsável por qualquer perda ou dano que você possa sofrer como resultado do uso ou acesso a quaisquer desses aplicativos, dados, conteúdo ou recursos de terceiros.
2026-05-17T18:43:05.2124782Z
2026-05-17T18:43:05.2126158Z 7.2 Você deve estar ciente de que os dados, o conteúdo e os recursos apresentados a você por meio de um aplicativo de terceiros podem estar protegidos por direitos de propriedade intelectual pertencentes aos provedores (ou a outras pessoas ou empresas em seu nome). Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados, conteúdo ou recursos (no todo ou em parte), a menos que tenha recebido permissão expressa dos respectivos proprietários.
2026-05-17T18:43:05.2127597Z
2026-05-17T18:43:05.2128409Z 7.3 Você reconhece que o uso de aplicativos, dados, conteúdo ou recursos de terceiros pode estar sujeito a termos separados entre você e o respectivo terceiro. Nesse caso, este Contrato de Licença não afeta sua relação jurídica com esses terceiros.
2026-05-17T18:43:05.2129253Z
2026-05-17T18:43:05.2129326Z 8. Usando APIs do Google
2026-05-17T18:43:05.2129441Z
2026-05-17T18:43:05.2129518Z 8.1 APIs do Google
2026-05-17T18:43:05.2129618Z
2026-05-17T18:43:05.2131198Z 8.1.1 Se você usar qualquer API para obter dados do Google, você reconhece que os dados podem estar protegidos por direitos de propriedade intelectual pertencentes ao Google ou às partes que fornecem os dados (ou a outras pessoas ou empresas em nome delas). O uso de qualquer API desse tipo pode estar sujeito a Termos de Serviço adicionais. Você não pode modificar, alugar, arrendar, emprestar, vender, distribuir ou criar trabalhos derivados com base nesses dados (no todo ou em parte), a menos que seja permitido pelos Termos de Serviço relevantes.
2026-05-17T18:43:05.2132679Z
2026-05-17T18:43:05.2133364Z 8.1.2 Se você usar qualquer API para recuperar dados de um usuário do Google, você reconhece e concorda que só poderá recuperar dados com o consentimento explícito do usuário e somente quando, e para os fins limitados para os quais, o usuário lhe deu permissão para fazê-lo.
2026-05-17T18:43:05.2134154Z
2026-05-17T18:43:05.2134243Z 9. Rescisão deste Contrato de Licença
2026-05-17T18:43:05.2134401Z
2026-05-17T18:43:05.2134677Z 9.1 Este Contrato de Licença continuará em vigor até ser rescindido por você ou pelo Google, conforme estabelecido abaixo.
2026-05-17T18:43:05.2135027Z
2026-05-17T18:43:05.2135361Z 9.2 Se desejar rescindir este Contrato de Licença, poderá fazê-lo cessando a utilização do GDK e quaisquer credenciais de desenvolvedor relevantes.
2026-05-17T18:43:05.2135784Z
2026-05-17T18:43:05.2137603Z 9.3 O Google poderá, a qualquer momento, rescindir este Contrato de Licença com você se: (A) você violar qualquer disposição deste Contrato de Licença; ou (B) o Google for obrigado a fazê-lo por lei; ou (C) o parceiro com quem o Google ofereceu certas partes do GDK (como APIs) a você tiver encerrado seu relacionamento com o Google ou deixado de oferecer certas partes do GDK a você; ou (D) o Google decidir não fornecer mais o GDK ou certas partes do GDK a usuários no país em que você reside ou de onde você usa o serviço, ou se o fornecimento do GDK ou de certos serviços do GDK a você pelo Google, a critério exclusivo do Google, deixar de ser comercialmente viável.
2026-05-17T18:43:05.2139482Z
2026-05-17T18:43:05.2140885Z 9.4 Quando este Contrato de Licença chegar ao fim, todos os direitos, obrigações e responsabilidades legais que você e o Google tenham adquirido, estejam sujeitos (ou que tenham se acumulado ao longo do tempo enquanto este Contrato de Licença esteve em vigor) ou que estejam expressamente previstos para continuar indefinidamente, não serão afetados por esta rescisão, e as disposições do parágrafo 14.7 continuarão a se aplicar a tais direitos, obrigações e responsabilidades indefinidamente.
2026-05-17T18:43:05.2142236Z
2026-05-17T18:43:05.2142318Z 10. ISENÇÃO DE GARANTIAS
2026-05-17T18:43:05.2142452Z
2026-05-17T18:43:05.2143014Z 10.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O USO DO GDK É POR SUA CONTA E RISCO E QUE O GDK É FORNECIDO "NO ESTADO EM QUE SE ENCONTRA" E "CONFORME DISPONÍVEL", SEM GARANTIA DE QUALQUER TIPO POR PARTE DO GOOGLE.
2026-05-17T18:43:05.2143559Z
2026-05-17T18:43:05.2144273Z 10.2 O USO DO GDK E DE QUALQUER MATERIAL BAIXADO OU OBTIDO DE OUTRA FORMA ATRAVÉS DO USO DO GDK É DE SUA INTEIRA RESPONSABILIDADE E RISCO, E VOCÊ É O ÚNICO RESPONSÁVEL POR QUALQUER DANO AO SEU SISTEMA DE COMPUTADOR OU OUTRO DISPOSITIVO OU PERDA DE DADOS QUE RESULTE DE TAL USO.
2026-05-17T18:43:05.2145070Z
2026-05-17T18:43:05.2145790Z 10.3 O GOOGLE EXPRESSAMENTE SE EXIME DE TODAS AS GARANTIAS E CONDIÇÕES DE QUALQUER TIPO, SEJAM ELAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO, MAS NÃO SE LIMITANDO ÀS GARANTIAS E CONDIÇÕES IMPLÍCITAS DE COMERCIABILIDADE, ADEQUAÇÃO A UM DETERMINADO FIM E NÃO VIOLAÇÃO.
2026-05-17T18:43:05.2146588Z
2026-05-17T18:43:05.2146673Z 11. LIMITAÇÃO DE RESPONSABILIDADE
2026-05-17T18:43:05.2146803Z
2026-05-17T18:43:05.2148104Z 11.1 VOCÊ COMPREENDE E CONCORDA EXPRESSAMENTE QUE O GOOGLE, SUAS SUBSIDIÁRIAS E AFILIADAS, E SEUS LICENCIADORES NÃO SERÃO RESPONSÁVEIS PERANTE VOCÊ SOB QUALQUER TEORIA DE RESPONSABILIDADE POR QUAISQUER DANOS DIRETOS, INDIRETOS, INCIDENTAIS, ESPECIAIS, CONSEQUENCIAIS OU EXEMPLARES QUE POSSAM SER INCORRIDOS POR VOCÊ, INCLUINDO QUALQUER PERDA DE DADOS, INDEPENDENTEMENTE DE O GOOGLE OU SEUS REPRESENTANTES TEREM SIDO AVISADOS OU DEVESSEM ESTAR CIENTES DA POSSIBILIDADE DE TAIS PERDAS OCORRER.
2026-05-17T18:43:05.2149471Z
2026-05-17T18:43:05.2149541Z 12. Indenização
2026-05-17T18:43:05.2149650Z
2026-05-17T18:43:05.2151802Z 12.1 Na máxima extensão permitida por lei, você concorda em defender, indenizar e isentar o Google, suas afiliadas e seus respectivos diretores, executivos, funcionários e agentes de quaisquer reivindicações, ações, processos ou procedimentos, bem como quaisquer perdas, responsabilidades, danos, custos e despesas (incluindo honorários advocatícios razoáveis) decorrentes de ou resultantes de (a) seu uso do GDK, (b) qualquer aplicativo que você desenvolva no GDK que infrinja qualquer direito autoral, marca registrada, segredo comercial, imagem comercial, patente ou outro direito de propriedade intelectual de qualquer pessoa ou difame qualquer pessoa ou viole seus direitos de publicidade ou privacidade, e (c) qualquer descumprimento por você deste Contrato de Licença.
2026-05-17T18:43:05.2153938Z
2026-05-17T18:43:05.2154022Z 13. Alterações ao Contrato de Licença
2026-05-17T18:43:05.2154176Z
2026-05-17T18:43:05.2154820Z 13.1 O Google poderá fazer alterações ao Contrato de Licença ao distribuir novas versões do GDK. Quando essas alterações forem feitas, o Google disponibilizará uma nova versão do Contrato de Licença no site onde o GDK é disponibilizado.
2026-05-17T18:43:05.2155674Z
2026-05-17T18:43:05.2155748Z 14. Termos Legais Gerais
2026-05-17T18:43:05.2155879Z
2026-05-17T18:43:05.2156732Z 14.1 Este Contrato de Licença constitui o acordo legal integral entre você e o Google e rege seu uso do GDK (excluindo quaisquer serviços que o Google possa fornecer a você sob um contrato escrito separado), e substitui completamente quaisquer acordos anteriores entre você e o Google em relação ao GDK.
2026-05-17T18:43:05.2157668Z
2026-05-17T18:43:05.2158554Z 14.2 Você concorda que, se o Google não exercer ou fizer valer qualquer direito ou recurso legal contido neste Contrato de Licença (ou do qual o Google se beneficie sob qualquer lei aplicável), isso não será considerado uma renúncia formal dos direitos do Google e que esses direitos ou recursos ainda estarão disponíveis para o Google.
2026-05-17T18:43:05.2159721Z
2026-05-17T18:43:05.2161265Z 14.3 Se qualquer tribunal competente para decidir sobre esta matéria declarar que qualquer disposição deste Contrato de Licença é inválida, essa disposição será removida deste Contrato de Licença sem afetar o restante do mesmo. As demais disposições deste Contrato de Licença permanecerão válidas e em pleno vigor.
2026-05-17T18:43:05.2162967Z
2026-05-17T18:43:05.2165342Z 14.4 Você reconhece e concorda que cada membro do grupo de empresas do qual o Google é a controladora será considerado terceiro beneficiário deste Contrato de Licença e que tais outras empresas terão o direito de exigir o cumprimento e se valer diretamente de qualquer disposição deste Contrato de Licença que lhes confira um benefício (ou direitos em seu favor). Além disso, nenhuma outra pessoa ou empresa será considerada terceiro beneficiário deste Contrato de Licença.
2026-05-17T18:43:05.2167384Z
2026-05-17T18:43:05.2168499Z 14.5 RESTRIÇÕES DE EXPORTAÇÃO. O GDK está sujeito às leis e regulamentos de exportação dos Estados Unidos. Você deve cumprir todas as leis e regulamentos de exportação nacionais e internacionais aplicáveis ​​ao GDK. Essas leis incluem restrições quanto a destinos, usuários finais e uso final.
2026-05-17T18:43:05.2169779Z
2026-05-17T18:43:05.2171340Z 14.6 Os direitos concedidos neste Contrato de Licença não podem ser cedidos ou transferidos por você ou pelo Google sem a prévia aprovação por escrito da outra parte. Nem você nem o Google poderão delegar suas responsabilidades ou obrigações sob este Contrato de Licença sem a prévia aprovação por escrito da outra parte.
2026-05-17T18:43:05.2172742Z
2026-05-17T18:43:05.2174519Z 14.7 Este Contrato de Licença e sua relação com o Google sob este Contrato de Licença serão regidos pelas leis do Estado da Califórnia, sem levar em consideração suas disposições sobre conflito de leis. Você e o Google concordam em se submeter à jurisdição exclusiva dos tribunais localizados no condado de Santa Clara, Califórnia, para resolver qualquer questão legal decorrente deste Contrato de Licença. Não obstante, você concorda que o Google ainda poderá solicitar medidas cautelares (ou um tipo equivalente de tutela jurisdicional urgente) em qualquer jurisdição.
2026-05-17T18:43:05.2176211Z
2026-05-17T18:43:05.2176294Z 19 de novembro de 2013
17-05-2026T18:43:05.2176480Z ---------------------------------------
2026-05-17T18:43:05.2176719Z Aceitar? (s/N):
2026-05-17T18:43:05.2176925Z 6/6: Licença mips-android-sysimage-license:
17-05-2026T18:43:05.2177191Z ---------------------------------------
2026-05-17T18:43:05.2179177Z MIPS Technologies, Inc. (“MIPS”) Contrato de Licença de Avaliação Interna para Imagens de Sistema MIPS Android™ para Kit de Desenvolvimento de Software (SDK) Android: Este Contrato de Licença de Avaliação Interna (este "Contrato") é celebrado entre a MIPS e você (como desenvolvedor individual ou pessoa jurídica – identificado abaixo como "Destinatário"). A MIPS disponibilizará o Software de Avaliação ao Destinatário conforme descrito, de acordo com os termos e condições estabelecidos abaixo.
2026-05-17T18:43:05.2180846Z
Ao clicar no botão “Aceitar”, baixar, instalar ou usar de qualquer outra forma os Materiais de Avaliação (definidos abaixo), você concorda em ficar vinculado aos termos deste Contrato, com vigência a partir da data em que clicar em “Aceitar” (a “Data de Vigência”), e, caso esteja fazendo isso em nome de uma entidade, você declara que está autorizado a vincular a entidade aos termos e condições deste Contrato. Se você não concordar em ficar vinculado aos termos e condições deste Contrato, não baixe, instale ou use os Materiais de Avaliação.
2026-05-17T18:43:05.2 184151Z
2026-05-17T18:43:05.2184309Z 1. DEFINIÇÕES. Estes termos terão os seguintes significados:
2026-05-17T18:43:05.2184546Z
2026-05-17T18:43:05.2185060Z 1.1 “MIPS” significa MIPS Technologies, Inc., uma corporação de Delaware com sede principal em: 955 East Arques Ave., Sunnyvale, CA 94085
2026-05-17T18:43:05.2185546Z
2026-05-17T18:43:05.2186118Z 1.2 “Software de Avaliação” significa imagens de sistema do emulador MIPS Android™ para o Kit de Desenvolvimento de Software (SDK) do Android, conforme disponibilizadas ao Destinatário.
2026-05-17T18:43:05.2186781Z
2026-05-17T18:43:05.2188173Z 1.3 “Materiais de Avaliação” significa, coletivamente, o Software de Avaliação (em formato de código-fonte e/ou código objeto) e a documentação (incluindo, sem limitação, quaisquer documentos de projeto, especificações, manuais de referência e outros materiais relacionados) relacionados ao Software de Avaliação, conforme disponibilizados ao Destinatário.
2026-05-17T18:43:05.2189156Z
2026-05-17T18:43:05.2193177Z 1.4 “Software de código aberto” significa qualquer software que exija (como condição de uso, modificação e/ou distribuição de tal software) que tal software ou outro software incorporado, derivado ou distribuído com tal software (a) seja divulgado ou distribuído na forma de código fonte; ou (b) seja licenciado pelo usuário a terceiros com o propósito de fazer e/ou distribuir trabalhos derivados; ou (c) seja redistribuível sem custo. O Software de Código Aberto inclui, sem limitação, software licenciado ou distribuído sob qualquer uma das seguintes licenças ou modelos de distribuição, ou licenças ou modelos de distribuição substancialmente semelhantes a qualquer um dos seguintes: (a) Licença Pública Geral GNU (GPL) ou Lesser/Library GPL (LGPL), (b) a Licença Artística (por exemplo, PERL), (c) a Licença Pública Mozilla, (d) a Licença Pública Netscape, (e) a Licença de Código-Fonte da Comunidade Sun (SCSL), (f) a Licença de Código-Fonte da Indústria Sun (SISL), (g) a licença de software Apache e (h) a Licença Pública Comum (CPL).
2026-05-17T18:43:05.2196859Z
2026-05-17T18:43:05.2198037Z 1.5 “Materiais de Pré-Lançamento” significa recursos de pré-lançamento designados como “alfa” ou “beta”, que podem não ser totalmente funcionais, que a MIPS pode modificar substancialmente na produção de qualquer versão de produção dos Materiais de Avaliação e/ou que ainda estão em desenvolvimento pela MIPS e/ou pelos fornecedores da MIPS.
2026-05-17T18:43:05.2198960Z
2026-05-17T18:43:05.2200773Z 2. OBJETIVO. A MIPS deseja disponibilizar os Materiais de Avaliação ao Destinatário exclusivamente para sua avaliação interna do Software de Avaliação, a fim de determinar a conveniência de cooperar com a MIPS no desenvolvimento de produtos compatíveis com o Software de Avaliação e/ou para aconselhar a MIPS sobre possíveis modificações no Software de Avaliação. O Destinatário não poderá divulgar, distribuir, modificar (exceto para facilitar a avaliação interna mencionada acima) ou fazer uso comercial dos Materiais de Avaliação ou de quaisquer modificações dos Materiais de Avaliação.
2026-05-17T18:43:05.2202526Z
2026-05-17T18:43:05.2203777Z OS MATERIAIS DE AVALIAÇÃO SÃO FORNECIDOS APENAS PARA FINS DE AVALIAÇÃO E NÃO PODEM SER MODIFICADOS (EXCETO PARA FACILITAR A AVALIAÇÃO INTERNA), DISTRIBUÍDOS PELO DESTINATÁRIO OU INCORPORADOS AOS PRODUTOS OU SOFTWARE DO DESTINATÁRIO. ENTRE EM CONTATO COM UM REPRESENTANTE DE VENDAS DA MIPS PARA SABER MAIS SOBRE A DISPONIBILIDADE E O CUSTO DE UMA VERSÃO COMERCIAL DO SOFTWARE DE AVALIAÇÃO.
2026-05-17T18:43:05.2204889Z
2026-05-17T18:43:05.2205698Z 3. TÍTULO. A titularidade dos Materiais de Avaliação permanece com a MIPS ou seus fornecedores. O destinatário não poderá hipotecar, penhorar ou onerar os Materiais de Avaliação de qualquer forma. O destinatário deverá devolver todos os Materiais de Avaliação, sem reter cópias, após o término ou expiração deste Contrato.
2026-05-17T18:43:05.2206577Z
2026-05-17T18:43:05.2211981Z 4. LICENÇA. A MIPS concede ao Destinatário uma licença pessoal, intransferível, não exclusiva e isenta de royalties, sob seus direitos autorais, para usar o Software de Avaliação apenas para os fins descritos no parágrafo 2 acima e apenas por um período que se inicia na Data de Vigência e se estende até o primeiro aniversário da Data de Vigência (o “Período de Avaliação”). Salvo comunicação em contrário por escrito da MIPS ao Destinatário, caso o Software de Avaliação seja fornecido em mais de uma versão ou lançamento (cada um, uma “Versão”), a concessão de licença nesta Seção 4 e o Período de Avaliação se aplicarão a cada Versão, sendo que, nesse caso, o Período de Avaliação terá início na data em que a Versão for disponibilizada ao público em geral e continuará até o primeiro aniversário dessa data. O Destinatário não poderá fazer modificações no Software de Avaliação. O Destinatário não poderá desmontar, realizar engenharia reversa ou descompilar qualquer software que não seja fornecido ao Destinatário em formato de código-fonte.
2026-05-17T18:43:05.2217552Z
2026-05-17T18:43:05.2217559Z
2026-05-17T18:43:05.2219409Z Exceto conforme previsto neste documento, nenhuma outra licença, expressa ou implícita, por preclusão ou de outra forma, para quaisquer outros direitos de propriedade intelectual da MIPS é concedida ao destinatário. Além do que está expressamente estabelecido no parágrafo 2 acima, nenhum direito de copiar, reproduzir, modificar ou criar obras derivadas dos materiais de avaliação é concedido neste documento.
2026-05-17T18:43:05.2221743Z
2026-05-17T18:43:05.2223187Z 5. SEM OBRIGAÇÃO. O destinatário não terá a obrigação de comprar ou licenciar qualquer produto da MIPS. A MIPS e seus fornecedores não terão a obrigação de fornecer suporte ou desenvolver uma versão não avaliativa do Software de Avaliação, nem de licenciar qualquer versão do mesmo.
2026-05-17T18:43:05.2224813Z
2026-05-17T18:43:05.2230030Z 6. MODIFICAÇÕES. Este Acordo não obriga o Beneficiário a fornecer ao MIPS comentários ou sugestões sobre os Materiais de Avaliação. Contudo, caso o Destinatário forneça à MIPS comentários ou sugestões para a modificação, correção, melhoria ou aprimoramento (a) dos Materiais de Avaliação ou (b) dos produtos ou processos da MIPS que possam incorporar os Materiais de Avaliação, o Destinatário concorda em conceder, e por meio deste instrumento concede, à MIPS uma licença não exclusiva, irrevogável, mundial, totalmente paga e isenta de royalties, com o direito de sublicenciar os licenciados e clientes da MIPS, sob os direitos de propriedade intelectual do Destinatário, para usar e divulgar tais comentários e sugestões da maneira que a MIPS escolher e para exibir, executar, copiar, fabricar, mandar fabricar, usar, vender, oferecer para venda, importar e de outra forma dispor dos produtos da MIPS e de seus sublicenciados que incorporem tais comentários e sugestões, de qualquer maneira e por qualquer meio que a MIPS escolher, sem referência à fonte.
2026-05-17T18:43:05.2234046Z
2026-05-17T18:43:05.2235608Z 7. ISENÇÃO DE GARANTIA. A MIPS E SEUS FORNECEDORES NÃO OFERECEM GARANTIAS COM RELAÇÃO AOS MATERIAIS DE AVALIAÇÃO, SEJAM ELAS EXPRESSAS OU IMPLÍCITAS, INCLUINDO QUAISQUER GARANTIAS IMPLÍCITAS DE COMERCIABILIDADE OU ADEQUAÇÃO A UM FIM ESPECÍFICO, OU QUALQUER GARANTIA IMPLÍCITA DE NÃO VIOLAÇÃO COM RELAÇÃO À PROPRIEDADE INTELECTUAL DE TERCEIROS. O DESTINATÁRIO RECONHECE E CONCORDA QUE OS MATERIAIS DE AVALIAÇÃO SÃO FORNECIDOS "NO ESTADO EM QUE SE ENCONTRAM", SEM GARANTIA DE QUALQUER TIPO.
2026-05-17T18:43:05.2236954Z
2026-05-17T18:43:05.2238644Z 8. LIMITAÇÃO DE RESPONSABILIDADE. A MIPS E SEUS FORNECEDORES NÃO SERÃO RESPONSÁVEIS POR QUAISQUER DANOS MATERIAIS, LESÕES CORPORAIS, LUCROS CESSANTES, INTERRUPÇÃO DE NEGÓCIOS OU POR QUAISQUER DANOS DIRETOS, INDIRETOS, ESPECIAIS, CONSEQUENCIAIS OU INCIDENTAIS, INDEPENDENTEMENTE DA CAUSA OU DA AÇÃO ALEGADA, SEJA POR VIOLAÇÃO DE GARANTIA, CONTRATO, RESPONSABILIDADE OBJETIVA OU DE OUTRA FORMA, INCLUINDO, SEM LIMITAÇÃO, POR ATO ILÍCITO OU OUTRA TEORIA JURÍDICA. A MIPS e seus fornecedores se eximem de toda e qualquer responsabilidade, incluindo a responsabilidade por violação de quaisquer direitos de propriedade intelectual de qualquer tipo relacionados aos materiais de avaliação.
2026-05-17T18:43:05.2240544Z
2026-05-17T18:43:05.2241185Z 9. EXPIRAÇÃO. A MIPS poderá rescindir este Contrato imediatamente após uma violação por parte do Destinatário ou de outra forma a critério razoável da MIPS e mediante notificação ao Destinatário com cinco (5) dias úteis de antecedência.
2026-05-17T18:43:05.2241791Z
2026-05-17T18:43:05.2241862Z 10. GERAL.
2026-05-17T18:43:05.2241965Z
2026-05-17T18:43:05.2244915Z 10.1 Lei Aplicável. Este Contrato será regido pelas leis da Califórnia, excluindo-se as normas de conflito de leis. Com exceção dos direitos da MIPS de exercer seus direitos de propriedade intelectual e quaisquer obrigações de confidencialidade sob este Contrato ou quaisquer licenças distribuídas com os Materiais de Avaliação, todas as disputas e quaisquer reivindicações decorrentes deste Contrato ou a ele relacionadas estarão sujeitas à jurisdição e foro exclusivos dos tribunais estaduais e federais localizados no Condado de Santa Clara, Califórnia. Cada parte concorda com a jurisdição e o foro dos tribunais mencionados na frase anterior. As partes concordam que a Convenção das Nações Unidas sobre Contratos de Compra e Venda Internacional de Mercadorias está expressamente excluída de sua aplicação a este Contrato. As partes consentem com a jurisdição pessoal dos tribunais acima mencionados.
2026-05-17T18:43:05.2247473Z
2026-05-17T18:43:05.2248893Z 10.2 Recursos. O Destinatário reconhece e concorda que qualquer violação das obrigações de confidencialidade sob este Contrato ou quaisquer licenças distribuídas com os Materiais de Avaliação, bem como qualquer divulgação, comercialização ou uso público dos Materiais de Avaliação, causaria danos irreparáveis ​​à MIPS e, portanto, o Destinatário concorda em consentir, e por meio deste instrumento consente, com a concessão de uma liminar por qualquer tribunal de jurisdição competente em caso de violação real ou iminente.
2026-05-17T18:43:05.2250675Z
2026-05-17T18:43:05.2252501Z 10.3 Cessão. O Destinatário não poderá delegar, ceder ou transferir este Contrato, a licença concedida ou quaisquer direitos, obrigações ou deveres do Destinatário aqui previstos, expressamente, implicitamente, por força de lei, por meio de fusão (independentemente de o Destinatário ser a entidade sobrevivente) ou aquisição, ou de qualquer outra forma, e qualquer tentativa de fazê-lo, sem o prévio consentimento expresso por escrito da MIPS, será ineficaz, nula e sem efeito. A MIPS poderá ceder livremente este Contrato, bem como seus direitos e obrigações aqui previstos, a seu exclusivo critério.
2026-05-17T18:43:05.2254094Z
2026-05-17T18:43:05.2255517Z 10.4 Acordo Integral. Este Acordo constitui o acordo integral entre o Beneficiário e a MIPS e substitui integralmente todos e quaisquer acordos orais ou escritos anteriormente existentes entre o Beneficiário e a MIPS com relação ao objeto deste Acordo. Este Acordo somente poderá ser alterado ou complementado por documento escrito que faça referência explícita a este Acordo e que seja assinado ou de outra forma aceito por representantes devidamente autorizados do Beneficiário e da MIPS.
2026-05-17T18:43:05.2256948Z
2026-05-17T18:43:05.2258286Z 10.5 Divisibilidade. Caso qualquer disposição deste Contrato seja definitivamente considerada inexequível ou inválida sob qualquer lei aplicável, tal inexequibilidade ou invalidade não tornará este Contrato inexequível ou inválido como um todo e, nesse caso, tal disposição inexequível ou inválida deverá ser interpretada de forma a melhor atingir os objetivos da referida disposição dentro dos limites da lei aplicável ou das decisões judiciais aplicáveis.
2026-05-17T18:43:05.2259681Z
2026-05-17T18:43:05.2264272Z 10.6 Regulamentos de Exportação / Controle de Exportação. O destinatário não poderá exportar, direta ou indiretamente, qualquer produto, serviço, dado técnico ou sistema que incorpore os Materiais de Avaliação sem antes obter todas as licenças ou aprovações necessárias do Departamento de Comércio dos EUA ou de qualquer outra agência ou departamento governamental dos Estados Unidos. Caso algum produto seja exportado dos Estados Unidos ou reexportado de um destino estrangeiro pelo destinatário, este deverá garantir que a distribuição e a exportação/reexportação ou importação do produto estejam em conformidade com todas as leis, regulamentos, ordens ou outras restrições aplicáveis ​​dos Regulamentos de Administração de Exportação dos EUA e do governo estrangeiro competente. O destinatário concorda que nem ele nem qualquer de suas subsidiárias exportará/reexportará quaisquer dados técnicos, processos, produtos ou serviços, direta ou indiretamente, para qualquer país para o qual o governo dos Estados Unidos ou qualquer agência deste, ou o governo estrangeiro de onde a remessa está sendo enviada, exija uma licença de exportação ou outra aprovação governamental, sem antes obter tal licença ou aprovação. O destinatário também concorda em implementar medidas para garantir que os funcionários estrangeiros estejam autorizados a receber qualquer informação controlada pelas leis de controle de exportação dos EUA. Uma exportação é considerada realizada quando a informação é divulgada a um cidadão estrangeiro, independentemente de sua localização.
2026-05-17T18:43:05.2268752Z
2026-05-17T18:43:05.2272203Z 10.7 Termos Especiais para Materiais de Pré-Lançamento. Se assim indicado na descrição do Software de Avaliação, o Software de Avaliação poderá conter Materiais de Pré-Lançamento. O destinatário compreende, reconhece e concorda que: (i) os Materiais de Pré-Lançamento podem não ter sido totalmente testados e podem conter bugs ou erros; (ii) os Materiais de Pré-Lançamento não são adequados para lançamento comercial em seu estado atual; (iii) as aprovações regulatórias para os Materiais de Pré-Lançamento (como UL ou FCC) não foram obtidas e, portanto, os Materiais de Pré-Lançamento podem não ser certificados para uso em determinados países ou ambientes ou podem não ser adequados para determinadas aplicações; e (iv) a MIPS não pode garantir que algum dia produzirá ou disponibilizará ao público uma versão de produção dos Materiais de Pré-Lançamento. A MIPS não tem qualquer obrigação de desenvolver e/ou lançar, oferecer à venda ou licenciar um produto final com base nos Materiais de Pré-Lançamento e pode optar unilateralmente por abandonar os Materiais de Pré-Lançamento ou qualquer plataforma de desenvolvimento a qualquer momento e sem qualquer obrigação ou responsabilidade perante o Destinatário ou qualquer outra pessoa.
2026-05-17T18:43:05.2275835Z
2026-05-17T18:43:05.2276438Z QUALQUER MATERIAL DE PRÉ-LANÇAMENTO NÃO É QUALIFICADO E, COMO TAL, É FORNECIDO "NO ESTADO EM QUE SE ENCONTRA" E "CONFORME DISPONÍVEL", POSSIVELMENTE COM FALHAS, E SEM QUALQUER DECLARAÇÃO OU GARANTIA DE QUALQUER TIPO.
2026-05-17T18:43:05.2276984Z
2026-05-17T18:43:05.2278935Z 10.8 Software de Código Aberto. Caso o Software de Código Aberto esteja incluído no Software de Avaliação, tal Software de Código Aberto será licenciado de acordo com o contrato de licença de software de código aberto aplicável, identificado nos comentários do software de código aberto nos arquivos de código-fonte aplicáveis ​​e/ou no cabeçalho do arquivo, conforme indicado no Software de Avaliação. Detalhes adicionais podem estar disponíveis (quando aplicável) na documentação online que acompanha o produto. Com relação ao software de código aberto, nada neste Contrato limita quaisquer direitos previstos em, ou concede direitos que substituam, os termos de qualquer contrato de licença de software de código aberto aplicável.
2026-05-17T18:43:05.2281125Z ---------------------------------------
2026-05-17T18:43:05.2281394Z Aceitar? (s/N): Todas as licenças do pacote SDK aceitas
2026-05-17T18:43:05.2281585Z
2026-05-17T18:43:05.2281798Z [comando]/usr/local/lib/android/sdk/cmdline-tools/16.0/bin/sdkmanager tools
2026-05-17T18:43:05.9070088Z Carregando informações do pacote...                                                  
2026-05-17T18:43:05.9993029Z Carregando repositório local...                                                     
2026-05-17T18:43:05.9994539Z [ ] 3% Carregando repositório local...        
2026-05-17T18:43:06.0082912Z [ ] 3% Buscando repositório remoto...         
2026-05-17T18:43:06.3001307Z [= ] 3% Buscando repositório remoto...         
2026-05-17T18:43:06.3717993Z [= ] 4% Buscando repositório remoto...         
2026-05-17T18:43:06.4182786Z [= ] 5% Buscando repositório remoto...         
2026-05-17T18:43:06.4819241Z [== ] 5% Buscando repositório remoto...         
2026-05-17T18:43:06.5605601Z [== ] 6% Buscando repositório remoto...         
2026-05-17T18:43:06.6400583Z [== ] 7% Buscando repositório remoto...         
2026-05-17T18:43:06.6421516Z [== ] 7% Calculando atualizações...               
2026-05-17T18:43:06.6545703Z [=== ] 8% Calculando atualizações...               
2026-05-17T18:43:06.6723453Z [=== ] 10% Atualizações de computação...              
2026-05-17T18:43:07.0426079Z [=== ] 10% Instalando o Emulador Android       
2026-05-17T18:43:07.1698227Z [=== ] 10% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.2452627Z [==== ] 10% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.4094616Z [==== ] 11% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.5025325Z [==== ] 12% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.5961234Z [===== ] 13% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.6786325Z [===== ] 14% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.7302057Z [===== ] 15% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.7714382Z [====== ] 15% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.8644490Z [====== ] 16% Baixando emulator-linux_x64-152
2026-05-17T18:43:07.9567994Z [====== ] 17% Baixando emulator-linux_x64-152
2026-05-17T18:43:08.0140730Z [======= ] 18% Baixando emulator-linux_x64-152
2026-05-17T18:43:08.0489453Z [======= ] 19% Baixando emulator-linux_x64-152
2026-05-17T18:43:08.0662938Z [======= ] 20% Baixando emulator-linux_x64-152
2026-05-17T18:43:08.0880031Z [======== ] 20% Baixando emulator-linux_x64-152
2026-05-17T18:43:08.1156512Z [======== ] 21% Baixando emulator-linux_x64-152
2026-05-17T18:43:08.1759633Z [======== ] 21% Descompactando...                      
2026-05-17T18:43:08.1763770Z [======== ] 21% Descompactando... emulador/            
2026-05-17T18:43:08.1764402Z [======== ] 21% Descompactando... emulator/resources/  
2026-05-17T18:43:08.2123415Z [======== ] 21% Descompactando... emulador/qsn         
2026-05-17T18:43:08.2247679Z [======== ] 21% Descompactando... emulador/emulador    
2026-05-17T18:43:08.3157784Z [======== ] 21% Descompactando... emulador/netsimd     
2026-05-17T18:43:08.3847090Z [======== ] 22% Descompactando... emulador/netsimd     
2026-05-17T18:43:08.3848073Z [======== ] 22% Descompactando... emulator/bin64/      
2026-05-17T18:43:08.3851473Z [======== ] 22% Descompactando... emulator/android-info
2026-05-17T18:43:08.3852593Z [======== ] 22% Descompactando... emulator/qemu/       
2026-05-17T18:43:08.3865688Z [======== ] 22% Descompactando... emulator/NOTICE.txt  
2026-05-17T18:43:08.4086466Z [======== ] 22% Descompactando... emulator/crashpad_han
2026-05-17T18:43:08.4091315Z [======== ] 22% Descompactando... emulator/source.prope
2026-05-17T18:43:08.4628169Z [======== ] 22% Descompactando... emulator/nimble_bridg
2026-05-17T18:43:08.4630087Z [======== ] 22% Descompactando... emulador/LICENÇA     
2026-05-17T18:43:08.4630767Z [======== ] 22% Descompactando... emulator/lib/        
2026-05-17T18:43:08.4716005Z [======== ] 22% Descompactando... emulator/qemu-img    
2026-05-17T18:43:08.4716683Z [======== ] 22% Descompactando... emulator/include/    
2026-05-17T18:43:08.4720111Z [======== ] 22% Descompactando... emulator/NOTICE.csv  
2026-05-17T18:43:08.4720848Z [======== ] 22% Descompactando... emulator/lib64/      
2026-05-17T18:43:08.4894985Z [========] 22% Descompactando... emulador/emulador-che
2026-05-17T18:43:08.5112981Z [======== ] 22% Descompactando... emulator/crashreport
2026-05-17T18:43:08.5115803Z [======== ] 22% Descompactando... emulator/mksdcard    
2026-05-17T18:43:08.5116759Z [======== ] 22% Descompactando... emulator/resources/de
2026-05-17T18:43:08.5491071Z [======== ] 22% Descompactando... emulator/resources/To
2026-05-17T18:43:08.5498693Z [======== ] 22% Descompactando... emulator/resources/ma
2026-05-17T18:43:08.5536374Z [======== ] 22% Descompactando... emulator/resources/de
2026-05-17T18:43:08.5548149Z [======== ] 22% Descompactando... emulator/resources/sk
2026-05-17T18:43:08.5549071Z [======== ] 22% Descompactando... emulator/resources/ma
2026-05-17T18:43:08.5549826Z [======== ] 22% Descompactando... emulator/resources/po
2026-05-17T18:43:08.5640862Z [======== ] 22% Descompactando... emulator/resources/ma
2026-05-17T18:43:08.5709764Z [======== ] 22% Descompactando... emulator/resources/sk
2026-05-17T18:43:08.5723026Z [======== ] 22% Descompactando... emulator/resources/ma
2026-05-17T18:43:08.5759669Z [======== ] 22% Descompactando... emulator/bin64/e2fsck
2026-05-17T18:43:08.5794148Z [======== ] 22% Descompactando... emulator/bin64/fsck.e
2026-05-17T18:43:08.5815488Z [======== ] 22% Descompactando... emulator/bin64/tune2f
2026-05-17T18:43:08.5830851Z [======== ] 22% Descompactando... emulator/bin64/resize
2026-05-17T18:43:08.5854735Z [======== ] 22% Descompactando... emulator/bin64/mkfs.e
2026-05-17T18:43:08.6096941Z [======== ] 22% Descompactando... emulator/qemu/linux-x
2026-05-17T18:43:08.9785528Z [========= ] 23% Descompactando... emulator/qemu/linux-x
2026-05-17T18:43:09.3226119Z [========= ] 24% Descompactando... emulator/qemu/linux-x
2026-05-17T18:43:09.4873815Z [========= ] 25% Descompactando... emulator/qemu/linux-x
2026-05-17T18:43:09.6552195Z [========== ] 25% Descompactando... emulator/qemu/linux-x
2026-05-17T18:43:09.6554059Z [========== ] 25% Descompactando... emulator/lib/emulator
2026-05-17T18:43:09.6556106Z [========== ] 25% Descompactando... emulator/lib/rtc_serv
2026-05-17T18:43:09.6560287Z [========== ] 25% Descompactando... emulator/lib/advanced
2026-05-17T18:43:09.6561543Z [========== ] 25% Descompactando... emulator/lib/cmake/  
2026-05-17T18:43:09.6564739Z [========== ] 25% Descompactando... emulator/lib/emulator
2026-05-17T18:43:09.6566969Z [========== ] 25% Descompactando... emulator/lib/control_
2026-05-17T18:43:09.6570699Z [========== ] 25% Descompactando... emulator/lib/emulated
2026-05-17T18:43:09.6573779Z [========== ] 25% Descompactando... emulator/lib/rtc_serv
2026-05-17T18:43:09.6577150Z [========== ] 25% Descompactando... emulator/lib/emu-orig
2026-05-17T18:43:09.6580306Z [========== ] 25% Descompactando... emulator/lib/hardware
2026-05-17T18:43:09.6581382Z [========== ] 25% Descompactando... emulator/lib/pkgconfi
2026-05-17T18:43:09.6581969Z [========== ] 25% Descompactando... emulator/lib/pc-bios/
2026-05-17T18:43:09.6585987Z [========== ] 25% Descompactando... emulator/lib/snapshot
2026-05-17T18:43:09.6586695Z [========== ] 25% Descompactando... emulator/lib/adb_serv
2026-05-17T18:43:09.6593269Z [========== ] 25% Descompactando... emulator/lib/hostapd.
2026-05-17T18:43:09.6595602Z [========== ] 25% Descompactando... emulator/lib/grpc_end
2026-05-17T18:43:09.6612434Z [========== ] 25% Descompactando... emulator/lib/ca-bundl
2026-05-17T18:43:09.6614821Z [========== ] 25% Descompactando... emulator/lib/ui_contr
2026-05-17T18:43:09.6618510Z [========== ] 25% Descompactando... emulator/lib/snapshot
2026-05-17T18:43:09.6621225Z [========== ] 25% Descompactando... emulator/lib/ice_conf
2026-05-17T18:43:09.6802591Z [========== ] 25% Descompactando... emulator/lib/libflatb
2026-05-17T18:43:09.6912599Z [========== ] 26% Descompactando... emulator/lib/libflatb
2026-05-17T18:43:09.6919990Z [========== ] 26% Descompactando... emulator/lib/emulator
2026-05-17T18:43:09.6922539Z [========== ] 26% Descompactando... emulator/lib/waterfal
2026-05-17T18:43:09.6926012Z [========== ] 26% Descompactando... emulator/lib/emulated
2026-05-17T18:43:09.6939432Z [========== ] 26% Descompactando... emulator/lib/cmake/fl
2026-05-17T18:43:09.6940493Z [========== ] 26% Descompactando... emulator/lib/pkgconfi
2026-05-17T18:43:09.7112247Z [========== ] 26% Descompactando... emulator/lib/pc-bios/
2026-05-17T18:43:09.7170288Z [========== ] 26% Descompactando... emulator/include/flat
2026-05-17T18:43:09.7243587Z [========== ] 26% Descompactando... emulator/lib64/libgli
2026-05-17T18:43:09.7366735Z [========== ] 26% Descompactando... emulator/lib64/libpro
2026-05-17T18:43:09.7367310Z [========== ] 26% Descompactando... emulator/lib64/qt/   
2026-05-17T18:43:09.7776815Z [========== ] 26% Descompactando... emulator/lib64/liband
2026-05-17T18:43:09.8489079Z [========== ] 26% Descompactando... emulator/lib64/libgfx
2026-05-17T18:43:09.8489505Z [========== ] 26% Descompactando... emulator/lib64/gles_l
2026-05-17T18:43:09.8496293Z [========== ] 26% Descompactando... emulator/lib64/liband
2026-05-17T18:43:09.8496644Z [========== ] 26% Descompactando... emulator/lib64/vulkan
2026-05-17T18:43:09.8496970Z [========== ] 26% Descompactando... emulator/lib64/gles_s
2026-05-17T18:43:09.8500221Z [========== ] 26% Descompactando... emulator/lib64/libemu
2026-05-17T18:43:09.8623486Z [========== ] 26% Descompactando... emulator/lib64/libpro
2026-05-17T18:43:10.0039481Z [========== ] 26% Descompactando... emulator/lib64/liband
2026-05-17T18:43:10.0056983Z [========== ] 26% Descompactando... emulator/lib64/libtcm
2026-05-17T18:43:10.0059640Z [========== ] 26% Descompactando... emulator/lib64/libima
2026-05-17T18:43:10.0125462Z [========== ] 26% Descompactando... emulator/lib64/libc++
2026-05-17T18:43:10.0379008Z [========== ] 26% Descompactando... emulator/lib64/liband
2026-05-17T18:43:10.0425623Z [========== ] 26% Descompactando... emulator/lib64/libabs
2026-05-17T18:43:10.0426282Z [========== ] 26% Descompactando... emulator/lib64/gles_a
2026-05-17T18:43:10.0495953Z [========== ] 26% Descompactando... emulator/lib64/libsha
2026-05-17T18:43:10.0560905Z [========== ] 26% Descompactando... emulator/lib64/libc++
2026-05-17T18:43:10.0565499Z [========== ] 26% Descompactando... emulator/lib64/qt/res
2026-05-17T18:43:10.0566275Z [========== ] 26% Descompactando... emulator/lib64/qt/lib
2026-05-17T18:43:10.0567092Z [========== ] 26% Descompactando... emulator/lib64/qt/tra
2026-05-17T18:43:10.0568150Z [========== ] 26% Descompactando... emulator/lib64/qt/plu
2026-05-17T18:43:10.0608125Z [========== ] 26% Descompactando... emulator/lib64/qt/res
2026-05-17T18:43:10.1333159Z [========== ] 27% Descompactando... emulator/lib64/qt/res
2026-05-17T18:43:10.2252737Z [========== ] 27% Descompactando... emulator/lib64/qt/lib
2026-05-17T18:43:10.6144627Z [=========== ] 28% Descompactando... emulator/lib64/qt/lib
2026-05-17T18:43:11.0257266Z [=========== ] 29% Descompactando... emulator/lib64/qt/lib
2026-05-17T18:43:11.1971844Z [=========== ] 30% Descompactando... emulator/lib64/qt/lib
2026-05-17T18:43:11.3482158Z [============ ] 30% Descompactando... emulator/lib64/qt/lib
2026-05-17T18:43:11.4114867Z [============ ] 30% Descompactando... emulator/lib64/qt/tra
2026-05-17T18:43:11.4580637Z [============ ] 31% Descompactando... emulator/lib64/qt/tra
2026-05-17T18:43:11.4696910Z [============ ] 31% Descompactando... emulator/lib64/qt/plu
2026-05-17T18:43:11.5549347Z [============ ] 31% Descompactando... emulator/lib64/gles_l
2026-05-17T18:43:11.7852582Z [============ ] 31% Descompactando... emulator/lib64/vulkan
2026-05-17T18:43:12.1234016Z [============ ] 32% Descompactando... emulator/lib64/vulkan
2026-05-17T18:43:12.1944151Z [============ ] 32% Descompactando... emulator/lib64/gles_s
2026-05-17T18:43:12.2542087Z [============ ] 32% Descompactando... emulator/lib64/gles_a
2026-05-17T18:43:12.2900675Z [============= ] 33% Descompactando... emulator/lib64/gles_a
2026-05-17T18:43:12.6867777Z [===================== ] 55% Descompactando... emulator/lib64/gles_a
2026-05-17T18:43:12.7319638Z [===================== ] 55% Instalando o emulador de ferramentas do SDK do Android
2026-05-17T18:43:12.7383163Z [===================== ] 55% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.7471705Z [====================== ] 55% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.7659960Z [====================== ] 56% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.7832073Z [====================== ] 57% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8019724Z [======================= ] 58% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8165371Z [======================= ] 59% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8255720Z [======================= ] 60% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8332028Z [======================== ] 60% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8518134Z [======================== ] 61% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8702774Z [======================== ] 62% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.8891069Z [========================= ] 63% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.9076386Z [========================= ] 64% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.9151565Z [========================= ] 65% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.9252726Z [========================== ] 65% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.9377036Z [========================== ] 66% Baixando sdk-tools-linux-433379
2026-05-17T18:43:12.9763201Z [========================== ] 66% Descompactando... emulator/lib64/gles_a
2026-05-17T18:43:12.9769401Z [========================== ] 66% Descompactando... tools/               
2026-05-17T18:43:12.9771010Z [========================== ] 66% Descompactando... tools/proguard/      
2026-05-17T18:43:12.9771850Z [========================== ] 66% Descompactando... tools/proguard/licens
2026-05-17T18:43:12.9772671Z [========================== ] 66% Descompactando... tools/proguard/lib/  
2026-05-17T18:43:12.9808343Z [========================== ] 66% Descompactando... tools/proguard/lib/pr
2026-05-17T18:43:12.9811195Z [========================== ] 66% Descompactando... tools/proguard/lib/re
2026-05-17T18:43:12.9820869Z [========================== ] 66% Descompactando... tools/proguard/lib/pr
2026-05-17T18:43:12.9824012Z [========================== ] 66% Descompactando... tools/proguard/ant/  
2026-05-17T18:43:12.9824790Z [========================== ] 66% Descompactando... tools/proguard/ant/ta
2026-05-17T18:43:12.9825486Z [========================== ] 66% Descompactando... tools/proguard/docs/
2026-05-17T18:43:12.9827201Z [========================== ] 66% Descompactando... tools/proguard/docs/f
2026-05-17T18:43:12.9834255Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9836298Z [========================== ] 66% Descompactando... tools/proguard/docs/d
2026-05-17T18:43:12.9839470Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9842580Z [========================== ] 66% Descompactando... tools/proguard/docs/F
2026-05-17T18:43:12.9846564Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9848880Z [========================== ] 66% Descompactando... tools/proguard/docs/l
2026-05-17T18:43:12.9853401Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9857083Z [========================== ] 66% Descompactando... tools/proguard/docs/d
2026-05-17T18:43:12.9862943Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9865268Z [========================== ] 66% Descompactando... tools/proguard/docs/r
2026-05-17T18:43:12.9867225Z [========================== ] 66% Descompactando... tools/proguard/docs/d
2026-05-17T18:43:12.9869924Z [========================== ] 66% Descompactando... tools/proguard/docs/t
2026-05-17T18:43:12.9871992Z [========================== ] 66% Descompactando... tools/proguard/docs/f
2026-05-17T18:43:12.9875949Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9881937Z [========================== ] 66% Descompactando... tools/proguard/docs/t
2026-05-17T18:43:12.9882730Z [========================== ] 66% Descompactando... tools/proguard/docs/i
2026-05-17T18:43:12.9884297Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9887026Z [========================== ] 66% Descompactando... tools/proguard/docs/m
2026-05-17T18:43:12.9889282Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9891437Z [========================== ] 66% Descompactando... tools/proguard/docs/q
2026-05-17T18:43:12.9894682Z [========================== ] 66% Descompactando... tools/proguard/docs/G
2026-05-17T18:43:12.9896647Z [========================== ] 66% Descompactando... tools/proguard/docs/t
2026-05-17T18:43:12.9908715Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9943838Z [========================== ] 66% Descompactando... tools/proguard/docs/m
2026-05-17T18:43:12.9946010Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9947667Z [========================== ] 66% Descompactando... tools/proguard/docs/G
2026-05-17T18:43:12.9949550Z [========================== ] 66% Descompactando... tools/proguard/docs/c
2026-05-17T18:43:12.9954394Z [========================== ] 66% Descompactando... tools/proguard/docs/a
2026-05-17T18:43:12.9961842Z [========================== ] 66% Descompactando... tools/proguard/docs/s
2026-05-17T18:43:12.9963860Z [========================== ] 66% Descompactando... tools/proguard/docs/d
2026-05-17T18:43:13.0021623Z [========================== ] 66% Descompactando... tools/proguard/exampl
2026-05-17T18:43:13.0022149Z [========================== ] 66% Descompactando... tools/proguard/bin/  
2026-05-17T18:43:13.0026150Z [========================== ] 66% Descompactando... tools/proguard/bin/pr
2026-05-17T18:43:13.0027934Z [========================== ] 66% Descompactando... tools/proguard/bin/re
2026-05-17T18:43:13.0029922Z [========================== ] 66% Descompactando... tools/proguard/README
2026-05-17T18:43:13.0034248Z [========================== ] 66% Descompactando... tools/proguard/progua
2026-05-17T18:43:13.0034809Z [========================== ] 66% Descompactando... tools/lib/           
2026-05-17T18:43:13.0070080Z [========================== ] 66% Descompactando... tools/lib/bcpkix-jdk1
2026-05-17T18:43:13.0077635Z [========================== ] 66% Descompactando... tools/lib/org-eclipse
2026-05-17T18:43:13.0088262Z [========================== ] 66% Descompactando... tools/lib/manifest-me
2026-05-17T18:43:13.0095511Z [========================== ] 66% Descompactando... tools/lib/jcommander-
2026-05-17T18:43:13.0108137Z [========================== ] 66% Descompactando... tools/lib/gson-2.3.ja
2026-05-17T18:43:13.0115097Z [========================== ] 66% Descompactando... tools/lib/ddms-26.0.0
2026-05-17T18:43:13.0118626Z [========================== ] 66% Descompactando... tools/lib/asm-tree-5.
2026-05-17T18:43:13.0161561Z [========================== ] 66% Descompactando... tools/lib/uast-26.0.0
2026-05-17T18:43:13.0171284Z [========================== ] 66% Descompactando... tools/lib/dexlib2-2.2
2026-05-17T18:43:13.0210986Z [========================== ] 67% Descompactando... tools/lib/dexlib2-2.2
2026-05-17T18:43:13.0213478Z [========================== ] 67% Descompactando... tools/lib/android.el
2026-05-17T18:43:13.0218605Z [========================== ] 67% Descompactando... tools/lib/apkanalyzer
2026-05-17T18:43:13.0343825Z [========================== ] 67% Descompactando... tools/lib/guava-22.0.
2026-05-17T18:43:13.0371083Z [========================== ] 67% Descompactando... tools/lib/lint-api-26
2026-05-17T18:43:13.0379137Z [========================== ] 67% Descompactando... tools/lib/baksmali-2.
2026-05-17T18:43:13.0383415Z [========================== ] 67% Descompactando... tools/lib/shared.jar
2026-05-17T18:43:13.0386987Z [========================== ] 67% Descompactando... tools/lib/jsr305-1.3.
2026-05-17T18:43:13.0410830Z [========================== ] 67% Descompactando... tools/lib/httpclient-
2026-05-17T18:43:13.0521921Z [========================== ] 67% Descompactando... tools/lib/ecj-4.6.1.j
2026-05-17T18:43:13.0525792Z [========================== ] 67% Descompactando... tools/lib/jobb-26.0.0
2026-05-17T18:43:13.0543814Z [========================== ] 67% Descompactando... tools/lib/jcommon-1.0
2026-05-17T18:43:13.0548071Z [========================== ] 67% Descompactando... tools/lib/kxml2-2.3.0
2026-05-17T18:43:13.0613933Z [========================== ] 67% Descompactando... tools/lib/jfreechart-
2026-05-17T18:43:13.0623060Z [========================== ] 67% Descompactando... tools/lib/common-26.0
2026-05-17T18:43:13.0680032Z [========================== ] 67% Descompactando... tools/lib/lint-checks
2026-05-17T18:43:13.0794082Z [========================== ] 67% Descompactando... tools/lib/kotlin-refl
2026-05-17T18:43:13.0797923Z [========================== ] 67% Descompactando... tools/lib/builder-mod
2026-05-17T18:43:13.0834883Z [========================== ] 67% Descompactando... tools/lib/sdklib-26.0
2026-05-17T18:43:13.0842314Z [========================== ] 67% Descompactando... tools/lib/layoutlib-a
2026-05-17T18:43:13.0843979Z [========================== ] 67% Descompactando... tools/lib/annotations
2026-05-17T18:43:13.0849274Z [========================== ] 67% Descompactando... tools/lib/fat32lib.ja
2026-05-17T18:43:13.0852890Z [========================== ] 67% Descompactando... tools/lib/jsr305-3.0.
2026-05-17T18:43:13.0905097Z [========================== ] 67% Descompactando... tools/lib/org-eclipse
2026-05-17T18:43:13.0914572Z [========================== ] 67% Descompactando... tools/lib/error_prone
2026-05-17T18:43:13.0916780Z [========================== ] 67% Descompactando... tools/lib/org-eclipse
2026-05-17T18:43:13.0932471Z [========================== ] 67% Descompactando... tools/lib/animal-snif
2026-05-17T18:43:13.0958041Z [========================== ] 67% Descompactando... tools/lib/asset-studi
2026-05-17T18:43:13.0985200Z [=========================== ] 68% Descompactando... tools/lib/asset-studi
2026-05-17T18:43:13.0997673Z [=========================== ] 68% Descompactando... tools/lib/repository-
2026-05-17T18:43:13.1001099Z [=========================== ] 68% Descompactando... tools/lib/dvlib-26.0.
2026-05-17T18:43:13.1030094Z [=========================== ] 68% Descompactando... tools/lib/jsilver-1.0
2026-05-17T18:43:13.1034605Z [=========================== ] 68% Descompactando... tools/lib/asm-5.1.jar
2026-05-17T18:43:13.1036938Z [=========================== ] 68% Descompactando... tools/lib/devices.xml
2026-05-17T18:43:13.1040172Z [=========================== ] 68% Descompactando... tools/lib/asm-analysi
2026-05-17T18:43:13.1062403Z [=========================== ] 68% Descompactando... tools/lib/hierarchyvi
2026-05-17T18:43:13.1069221Z [=========================== ] 68% Descompactando... tools/lib/monkeyrunne
2026-05-17T18:43:13.1074876Z [=========================== ] 68% Descompactando... tools/lib/uiautomator
2026-05-17T18:43:13.1076689Z [=========================== ] 68% Descompactando... tools/lib/archquery-2
2026-05-17T18:43:13.1081624Z [=========================== ] 68% Descompactando... tools/lib/chimpchat-2
2026-05-17T18:43:13.1084102Z [=========================== ] 68% Descompactando... tools/lib/explainer.j
2026-05-17T18:43:13.1102883Z [=========================== ] 68% Descompactando... tools/lib/ddmlib-26.0
2026-05-17T18:43:13.1106692Z [=========================== ] 68% Descompactando... tools/lib/swtmenubar-
2026-05-17T18:43:13.1202410Z [=========================== ] 68% Descompactando... tools/lib/osgi-4.0.0.
2026-05-17T18:43:13.1203185Z [=========================== ] 68% Descompactando... tools/lib/x86_64/    
2026-05-17T18:43:13.1276737Z [=========================== ] 68% Descompactando... tools/lib/x86_64/swt.
2026-05-17T18:43:13.1722802Z [=========================== ] 68% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.2490778Z [=========================== ] 69% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.3070155Z [=========================== ] 70% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.3518795Z [============================ ] 70% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.4768120Z [============================ ] 71% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.4769295Z [============================ ] 71% Descompactando... tools/lib/httpmime-4.
2026-05-17T18:43:13.4771171Z [============================ ] 71% Descompactando... tools/lib/annotations
2026-05-17T18:43:13.4786074Z [============================ ] 71% Descompactando... tools/lib/lint-26.0.0
2026-05-17T18:43:13.4790959Z [============================ ] 71% Descompactando... tools/lib/apkanalyzer
2026-05-17T18:43:13.4796278Z [============================ ] 71% Descompactando... tools/lib/binary-reso
2026-05-17T18:43:13.4802399Z [============================ ] 71% Descompactando... tools/lib/jopt-simple
2026-05-17T18:43:13.4810155Z [============================ ] 71% Descompactando... tools/lib/util-2.2.1.
2026-05-17T18:43:13.4827331Z [============================ ] 71% Descompactando... tools/lib/ddmuilib-26
2026-05-17T18:43:13.4841222Z [============================ ] 72% Descompactando... tools/lib/ddmuilib-26
2026-05-17T18:43:13.4888782Z [============================ ] 72% Descompactando... tools/lib/sdk-common-
2026-05-17T18:43:13.4898297Z [============================ ] 72% Descompactando... tools/lib/traceview-2
2026-05-17T18:43:13.4910978Z [============================ ] 72% Descompactando... tools/lib/httpcore-4.
2026-05-17T18:43:13.4913067Z [============================ ] 72% Descompactando... tools/lib/screenshot2
2026-05-17T18:43:13.4925317Z [============================ ] 72% Descompactando... tools/lib/commons-cod
2026-05-17T18:43:13.4927049Z [============================ ] 72% Descompactando... tools/lib/proguard-pr
2026-05-17T18:43:13.5502663Z [============================ ] 72% Descompactando... tools/lib/jython-stan
2026-05-17T18:43:13.5550912Z [============================= ] 73% Descompactando... tools/lib/jython-stan
2026-05-17T18:43:13.5553374Z [============================= ] 73% Descompactando... tools/lib/annotations
2026-05-17T18:43:13.5558204Z [============================= ] 73% Descompactando... tools/lib/commons-log
2026-05-17T18:43:13.5624582Z [============================= ] 73% Descompactando... tools/lib/protobuf-ja
2026-05-17T18:43:13.5628607Z [============================= ] 73% Descompactando... tools/lib/fakeadbserv
2026-05-17T18:43:13.5782046Z [============================= ] 73% Descompactando... tools/lib/bcprov-jdk1
2026-05-17T18:43:13.5782638Z [============================= ] 73% Descompactando... tools/lib/x86/       
2026-05-17T18:43:13.5850721Z [============================= ] 73% Descompactando... tools/lib/x86/swt.jar
2026-05-17T18:43:13.5894872Z [============================= ] 73% Descompactando... tools/lib/kotlin-stdl
2026-05-17T18:43:13.5918195Z [============================= ] 73% Descompactando... tools/lib/commons-com
2026-05-17T18:43:13.5954568Z [============================= ] 73% Descompactando... tools/lib/lombok-ast-
2026-05-17T18:43:13.5984771Z [============================= ] 73% Descompactando... tools/lib/trove4j-201
2026-05-17T18:43:13.6226055Z [============================= ] 73% Descompactando... tools/lib/intellij-co
2026-05-17T18:43:13.6373931Z [============================= ] 74% Descompactando... tools/lib/intellij-co
2026-05-17T18:43:13.6385784Z [============================= ] 74% Descompactando... tools/lib/jimfs-1.1.j
2026-05-17T18:43:13.6387847Z [============================= ] 74% Descompactando... tools/lib/j2objc-anno
2026-05-17T18:43:13.6394117Z [============================= ] 74% Descompactando... tools/lib/jfreechart-
2026-05-17T18:43:13.6833007Z [============================= ] 74% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.7216688Z [============================= ] 75% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.7580796Z [============================== ] 75% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.8357324Z [============================== ] 76% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.9532193Z [============================== ] 77% Descompactando... tools/lib/monitor-x86
2026-05-17T18:43:13.9535860Z [============================== ] 77% Descompactando... tools/lib/generator.j
2026-05-17T18:43:13.9537385Z [============================== ] 77% Descompactando... tools/source.properti
2026-05-17T18:43:13.9538075Z [============================== ] 77% Descompactando... tools/bin/           
2026-05-17T18:43:13.9540298Z [============================== ] 77% Descompactando... tools/bin/avdmanager
2026-05-17T18:43:13.9542912Z [============================== ] 77% Descompactando... tools/bin/jobb       
2026-05-17T18:43:13.9544483Z [==============================          ] 77% Descompactando... tools/bin/uiautomator
2026-05-17T18:43:13.9546852Z [============================== ] 77% Descompactando... tools/bin/apkanalyzer
2026-05-17T18:43:13.9548741Z [============================== ] 77% Descompactando... tools/bin/monkeyrunne
2026-05-17T18:43:13.9550622Z [============================== ] 77% Descompactando... tools/bin/archquery  
2026-05-17T18:43:13.9552773Z [============================== ] 77% Descompactando... tools/bin/sdkmanager
2026-05-17T18:43:13.9554615Z [============================== ] 77% Descompactando... tools/bin/lint       
2026-05-17T18:43:13.9556513Z [============================== ] 77% Descompactando... tools/bin/screenshot2
2026-05-17T18:43:13.9577442Z [============================== ] 77% Descompactando... tools/NOTICE.txt     
2026-05-17T18:43:13.9614833Z [============================== ] 77% Descompactando... tools/emulator       
2026-05-17T18:43:13.9639386Z [============================== ] 77% Descompactando... tools/emulator-check
2026-05-17T18:43:13.9641270Z [============================== ] 77% Descompactando... tools/monitor        
2026-05-17T18:43:13.9643461Z [============================== ] 77% Descompactando... tools/android        
2026-05-17T18:43:13.9703259Z [============================== ] 77% Descompactando... tools/mksdcard       
2026-05-17T18:43:13.9703887Z [============================== ] 77% Descompactando... ferramentas/suporte/       
2026-05-17T18:43:13.9708509Z [============================== ] 77% Descompactando... tools/support/typos-d
2026-05-17T18:43:13.9712981Z [============================== ] 77% Descompactando... tools/support/typos-e
2026-05-17T18:43:13.9714471Z [============================== ] 77% Descompactando... tools/support/annotat
2026-05-17T18:43:13.9722188Z [============================== ] 77% Descompactando... tools/support/typos-e
2026-05-17T18:43:13.9725240Z [============================== ] 77% Descompactando... tools/support/typost-t
2026-05-17T18:43:13.9729482Z [============================== ] 77% Descompactando... tools/support/typos-p
2026-05-17T18:43:13.9733085Z [============================== ] 77% Descompactando... tools/support/typos-i
2026-05-17T18:43:13.9735661Z [============================== ] 77% Descompactando... tools/support/typos-n
2026-05-17T18:43:13.9738936Z [============================== ] 77% Descompactando... tools/support/typos-h
2026-05-17T18:43:13.9897873Z [============================== ] 78% Descompactando... tools/support/typos-h
2026-05-17T18:43:13.9898449Z [=======================================] Descompactando 100%... ferramentas/suporte/erros de digitação-
2026-05-17T18:43:13.9933780Z
2026-05-17T18:43:14.0122968Z [comando]/usr/local/lib/android/sdk/cmdline-tools/16.0/bin/sdkmanager platform-tools
2026-05-17T18:43:14.7389792Z Carregando informações do pacote...                                                  
2026-05-17T18:43:14.8362453Z Carregando repositório local...                                                     
2026-05-17T18:43:14.8365126Z [ ] 3% Carregando repositório local...        
2026-05-17T18:43:14.8465397Z [ ] 3% Buscando repositório remoto...         
2026-05-17T18:43:15.1016850Z [= ] 3% Buscando repositório remoto...         
2026-05-17T18:43:15.1464153Z [= ] 4% Buscando repositório remoto...         
2026-05-17T18:43:15.1676761Z [= ] 5% Buscando repositório remoto...         
2026-05-17T18:43:15.2164810Z [== ] 5% Buscando repositório remoto...         
2026-05-17T18:43:15.2632659Z [== ] 6% Buscando repositório remoto...         
2026-05-17T18:43:15.3321708Z [== ] 7% Buscando repositório remoto...         
2026-05-17T18:43:15.3351309Z [== ] 7% Calculando atualizações...               
2026-05-17T18:43:15.3425429Z [=== ] 8% Atualizações de computação...               
2026-05-17T18:43:15.3488934Z [=== ] 10% Atualizações de computação...              
2026-05-17T18:43:15.3495985Z [=======================================] 100% Atualizações de computação...             
2026-05-17T18:43:15.3496546Z
2026-05-17T18:43:15.3762987Z ##[group]Executar sim | sdkmanager --licenses > /dev/null 2>&1 || true
2026-05-17T18:43:15.3763534Z [36;1myes | sdkmanager --licenses > /dev/null 2>&1 || true [0m
2026-05-17T18:43:15.3764037Z [36;1msdkmanager --install "platforms;android-34" "build-tools;34.0.0" "platform-tools" [0m
2026-05-17T18:43:15.3764481Z [36;1mecho "ANDROID_HOME=$ANDROID_HOME" >> $GITHUB_ENV [0m
2026-05-17T18:43:15.3764818Z [36;1mecho "$ANDROID_HOME/platform-tools" >> $GITHUB_PATH [0m
2026-05-17T18:43:15.3788240Z shell: /usr/bin/bash -e {0}
2026-05-17T18:43:15.3788473Z ambiente:
2026-05-17T18:43:15.3788758Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:15.3789202Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:15.3789745Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:43:15.3790030Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:43:15.3790286Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:43:15.3790974Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:43:15.3791423Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:43:15.3791724Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:43:15.3791978Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:43:15.3792239Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
17-05-2026T18:43:15.3792475Z ##[grupo final]
2026-05-17T18:43:16.8039631Z sim: saída padrão: Pipe quebrado
2026-05-17T18:43:17.5347767Z Carregando informações do pacote...                                                  
2026-05-17T18:43:17.6395945Z Carregando repositório local...                                                     
2026-05-17T18:43:17.6399004Z [ ] 3% Carregando repositório local...        
2026-05-17T18:43:17.6483505Z [ ] 3% Buscando repositório remoto...         
2026-05-17T18:43:17.9000759Z [= ] 3% Buscando repositório remoto...         
2026-05-17T18:43:18.0202259Z [= ] 4% Buscando repositório remoto...         
2026-05-17T18:43:18.0550696Z [= ] 5% Buscando repositório remoto...         
2026-05-17T18:43:18.1206115Z [== ] 5% Buscando repositório remoto...         
2026-05-17T18:43:18.2200978Z [== ] 6% Buscando repositório remoto...         
2026-05-17T18:43:18.2881704Z [== ] 7% Buscando repositório remoto...         
2026-05-17T18:43:18.2901510Z [== ] 7% Calculando atualizações...               
2026-05-17T18:43:18.2998645Z [=== ] 8% Calculando atualizações...               
2026-05-17T18:43:18.3050625Z [=== ] 10% Atualizações de computação...              
2026-05-17T18:43:18.3051747Z [========================================] 100% Atualizações de computação...             
2026-05-17T18:43:18.3052474Z
2026-05-17T18:43:18.3277968Z ##[group]Executar ações/setup-node@v4
2026-05-17T18:43:18.3278228Z com:
2026-05-17T18:43:18.3278396Z versão do nó: 20
2026-05-17T18:43:18.3278590Z sempre-autenticação: falso
2026-05-17T18:43:18.3278784Z check-latest: false
2026-05-17T18:43:18.3279082Z token: ***
2026-05-17T18:43:18.3279245Z env:
2026-05-17T18:43:18.3279507Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:18.3279951Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:18.3280321Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:43:18.3280911Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:43:18.3281177Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:43:18.3281577Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:43:18.3282012Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:43:18.3282341Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:43:18.3282589Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:43:18.3282851Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:43:18.3283087Z ##[endgroup]
2026-05-17T18:43:18.4977843Z Encontrado no cache em /opt/hostedtoolcache/node/20.20.2/x64
2026-05-17T18:43:18.4984936Z ##[group]Detalhes do ambiente
2026-05-17T18:43:21.7891782Z nó: v20.20.2
2026-05-17T18:43:21.7892164Z npm: 10.8.2
2026-05-17T18:43:21.7892441Z fio: 1.22.22
2026-05-17T18:43:21.7893046Z ##[endgroup]
2026-05-17T18:43:21.7964296Z ##[group]Execute npm install --prefer-offline
2026-05-17T18:43:21.7964619Z [36;1mnpm install --prefer-offline [0m
2026-05-17T18:43:21.7991086Z shell: /usr/bin/bash -e {0}
2026-05-17T18:43:21.7991461Z env:
2026-05-17T18:43:21.7991745Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:21.7992197Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:21.7992572Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:43:21.7992854Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:43:21.7993117Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:43:21.7993503Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:43:21.7993949Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:43:21.7994238Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:43:21.7994492Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:43:21.7994802Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:43:21.7995041Z ##[endgroup]
2026-05-17T18:43:28.4485404Z npm warn deprecated tar@6.2.1: Versões antigas do tar não são suportadas e contêm vulnerabilidades de segurança amplamente divulgadas, que foram corrigidas na versão atual. Por favor, atualize. Suporte para versões antigas pode ser adquirido (a preços exorbitantes) entrando em contato com i@izs.me
2026-05-17T18:43:28.5990795Z npm warn deprecated glob@9.3.5: Versões antigas do glob não são suportadas e contêm vulnerabilidades de segurança amplamente divulgadas, que foram corrigidas na versão atual. Por favor, atualize. Suporte para versões antigas pode ser adquirido (a preços exorbitantes) entrando em contato com i@izs.me
2026-05-17T18:43:29.3092021Z
2026-05-17T18:43:29.3092858Z adicionou 119 pacotes e auditou 120 pacotes em 7 segundos.
2026-05-17T18:43:29.3093312Z
2026-05-17T18:43:29.3093661Z 10 pacotes estão buscando financiamento.
2026-05-17T18:43:29.3094219Z execute `npm fund` para obter detalhes
2026-05-17T18:43:29.3317309Z
2026-05-17T18:43:29.3318051Z 2 vulnerabilidades de alta gravidade
2026-05-17T18:43:29.3318398Z
2026-05-17T18:43:29.3318979Z Para resolver todos os problemas (incluindo alterações que quebram a compatibilidade), execute:
2026-05-17T18:43:29.3319571Z npm audit fix --force
2026-05-17T18:43:29.3319815Z
2026-05-17T18:43:29.3320014Z Execute `npm audit` para obter detalhes.
2026-05-17T18:43:29.3449120Z ##[group]Executar npx cap copy android
2026-05-17T18:43:29.3449431Z [36;1mnpx cap copy android [0m
2026-05-17T18:43:29.3470793Z shell: /usr/bin/bash -e {0}
2026-05-17T18:43:29.3471019Z env:
2026-05-17T18:43:29.3471281Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:29.3471722Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:29.3472087Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:43:29.3472362Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:43:29.3472614Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:43:29.3472997Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:43:29.3473428Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:43:29.3473709Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:43:29.3473970Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:43:29.3474268Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:43:29.3474498Z ##[endgroup]
2026-05-17T18:43:30.6465910Z ✔ Copiando recursos da web de dist para android/app/src/main/assets/public em 11,88 ms
2026-05-17T18:43:30.6477228Z ✔ Criando capacitor.config.json em android/app/src/main/assets em 899.82μs
2026-05-17T18:43:30.6504479Z ✔ copiar android em 20,30ms
2026-05-17T18:43:30.6733753Z ##[group]Executar o wrapper do Gradle --gradle-version 8.6 --distribution-type bin
2026-05-17T18:43:30.6734550Z [36;1mgradle wrapper --gradle-version 8.6 --distribution-type bin [0m
2026-05-17T18:43:30.6735086Z [36;1mchmod +x gradlew [0m
2026-05-17T18:43:30.6766512Z shell: /usr/bin/bash -e {0}
2026-05-17T18:43:30.6766853Z env:
2026-05-17T18:43:30.6767308Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:30.6768008Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:43:30.6768901Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:43:30.6769359Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:43:30.6769799Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:43:30.6770744Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:43:30.6771501Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:43:30.6772071Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:43:30.6772529Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:43:30.6772982Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:43:30.6773424Z ##[endgroup]
2026-05-17T18:43:31.2367108Z
2026-05-17T18:43:31.2368023Z Bem-vindo ao Gradle 8.6!
2026-05-17T18:43:31.2368569Z
2026-05-17T18:43:31.2369234Z Aqui estão os destaques desta versão:
2026-05-17T18:43:31.2370075Z - Chave de criptografia configurável para o cache de configuração
2026-05-17T18:43:31.2370848Z - Melhorias na inicialização da compilação
2026-05-17T18:43:31.2371802Z - Melhorias na criação de builds
2026-05-17T18:43:31.2372097Z
2026-05-17T18:43:31.2375223Z Para mais detalhes, consulte https://docs.gradle.org/8.6/release-notes.html
2026-05-17T18:43:31.2375815Z
2026-05-17T18:43:31.6362788Z Iniciando um daemon do Gradle (as compilações subsequentes serão mais rápidas)
2026-05-17T18:44:10.1373500Z > Tarefa: wrapper
2026-05-17T18:44:10.2013042Z
2026-05-17T18:44:10.2021052Z COMPILAÇÃO CONCLUÍDA COM SUCESSO em 39s
2026-05-17T18:44:10.2023810Z 1 tarefa executável: 1 executada
2026-05-17T18:44:10.5237861Z ##[group]Execute ./gradlew assembleDebug --no-daemon --stacktrace 2>&1 | tail -150
2026-05-17T18:44:10.5238368Z [36;1m./gradlew assembleDebug --no-daemon --stacktrace 2>&1 | tail -150 [0m
2026-05-17T18:44:10.5259548Z shell: /usr/bin/bash -e {0}
17-05-2026T18:44:10.5259779Z ambiente:
2026-05-17T18:44:10.5260049Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:44:10.5260707Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:44:10.5261138Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:44:10.5261425Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:44:10.5261689Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:44:10.5262068Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:44:10.5262512Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:44:10.5262796Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:44:10.5263112Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:44:10.5263362Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:44:10.5263692Z GRADLE_OPTS: -Xmx3g -XX:MaxMetaspaceSize=512m -Dfile.encoding=UTF-8
2026-05-17T18:44:10.5264007Z JAVA_TOOL_OPTIONS: -Xmx3g
2026-05-17T18:44:10.5264208Z ##[endgroup]
2026-05-17T18:44:33.1493360Z Para respeitar as configurações da JVM para esta compilação, um processo Daemon de uso único será criado. Para mais informações, consulte https://docs.gradle.org/8.6/userguide/gradle_daemon.html#sec:disabling_the_daemon na documentação do Gradle.
2026-05-17T18:44:33.1495089Z O daemon será interrompido ao final da compilação.
2026-05-17T18:44:33.1495470Z > Tarefa :app:preBuild ATUALIZADA
2026-05-17T18:44:33.1495813Z > Tarefa :app:preDebugBuild ATUALIZADA
2026-05-17T18:44:33.1496217Z > Tarefa :app:mergeDebugNativeDebugMetadata SEM ORIGEM
2026-05-17T18:44:33.1496675Z > Tarefa :app:checkKotlinGradlePluginConfigurationErrors
2026-05-17T18:44:33.1497090Z > Tarefa :app:checkDebugAarMetadata FALHOU
2026-05-17T18:44:33.1497265Z
2026-05-17T18:44:33.1497452Z FALHA: A compilação falhou com uma exceção.
2026-05-17T18:44:33.1497631Z
2026-05-17T18:44:33.1497746Z * O que deu errado:
2026-05-17T18:44:33.1498153Z A execução da tarefa ':app:checkDebugAarMetadata' falhou.
2026-05-17T18:44:33.1498689Z > Não foi possível resolver todos os arquivos para a configuração ':app:debugRuntimeClasspath'.
2026-05-17T18:44:33.1499203Z > Não foi possível encontrar com.getcapacitor:capacitor-android:6.1.2.
2026-05-17T18:44:33.1499594Z Pesquisado nos seguintes locais:
2026-05-17T18:44:33.1500255Z - https://dl.google.com/dl/android/maven2/com/getcapacitor/capacitor-android/6.1.2/capacitor-android-6.1.2.pom
2026-05-17T18:44:33.1501730Z - https://repo.maven.apache.org/maven2/com/getcapacitor/capacitor-android/6.1.2/capacitor-android-6.1.2.pom
2026-05-17T18:44:33.1502242Z Requerido por:
2026-05-17T18:44:33.1502465Z projeto :app
2026-05-17T18:44:33.1502609Z
2026-05-17T18:44:33.1502690Z * Tente:
2026-05-17T18:44:33.1503054Z > Execute com a opção --info ou --debug para obter mais informações de registro.
2026-05-17T18:44:33.1503465Z > Execute com --scan para obter informações completas.
2026-05-17T18:44:33.1503829Z > Obtenha mais ajuda em https://help.gradle.org.
2026-05-17T18:44:33.1504006Z
2026-05-17T18:44:33.1504113Z * Exceção:
2026-05-17T18:44:33.1504693Z org.gradle.api.tasks.TaskExecutionException: A execução da tarefa ':app:checkDebugAarMetadata' falhou.
2026-05-17T18:44:33.1505635Z em org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:38)
2026-05-17T18:44:33.1506624Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-05-17T18:44:33.1507528Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-05-17T18:44:33.1508396Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-05-17T18:44:33.1509600Z em org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-05-17T18:44:33.1511276Z em org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-05-17T18:44:33.1512361Z em org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-05-17T18:44:33.1513271Z em org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-05-17T18:44:33.1514188Z em org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-05-17T18:44:33.1515089Z em org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-05-17T18:44:33.1515973Z em org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-05-17T18:44:33.1516871Z em org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-05-17T18:44:33.1517784Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-05-17T18:44:33.1518599Z em org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-05-17T18:44:33.1519531Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-05-17T18:44:33.1520756Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-05-17T18:44:33.1521942Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-05-17T18:44:33.1523031Z em org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-05-17T18:44:33.1524053Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-05-17T18:44:33.1525301Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-05-17T18:44:33.1526278Z em org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-05-17T18:44:33.1527077Z em org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-05-17T18:44:33.1527901Z em org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-05-17T18:44:33.1528877Z em org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-05-17T18:44:33.1530188Z Causado por: org.gradle.api.internal.artifacts.ivyservice.DefaultLenientConfiguration$ArtifactResolveException: Não foi possível resolver todos os arquivos para a configuração ':app:debugRuntimeClasspath'.
2026-05-17T18:44:33.1531543Z em org.gradle.api.internal.artifacts.ResolveExceptionContextualizer.mapFailure(ResolveExceptionContextualizer.java:81)
2026-05-17T18:44:33.1532576Z em org.gradle.api.internal.artifacts.ResolveExceptionContextualizer.mapFailures(ResolveExceptionContextualizer.java:60)
2026-05-17T18:44:33.1533689Z em org.gradle.api.internal.artifacts.configurations.DefaultConfiguration$DefaultResolutionHost.mapFailure(DefaultConfiguration.java:2321)
2026-05-17T18:44:33.1534695Z em org.gradle.api.internal.artifacts.configurations.ResolutionHost.rethrowFailure(ResolutionHost.java:30)
2026-05-17T18:44:33.1536075Z em org.gradle.api.internal.artifacts.configurations.ResolutionBackedFileCollection.maybeThrowResolutionFailures(ResolutionBackedFileCollection.java:84)
2026-05-17T18:44:33.1537371Z em org.gradle.api.internal.artifacts.configurations.ResolutionBackedFileCollection.visitContents(ResolutionBackedFileCollection.java:74)
2026-05-17T18:44:33.1538489Z em org.gradle.api.internal.file.AbstractFileCollection.visitStructure(AbstractFileCollection.java:361)
2026-05-17T18:44:33.1539385Z em org.gradle.api.internal.file.CompositeFileCollection.lambda$visitContents$0(CompositeFileCollection.java:113)
2026-05-17T18:44:33.1540199Z em org.gradle.api.internal.file.collections.UnpackingVisitor.add(UnpackingVisitor.java:67)
2026-05-17T18:44:33.1541093Z em org.gradle.api.internal.file.collections.UnpackingVisitor.add(UnpackingVisitor.java:92)
2026-05-17T18:44:33.1542063Z em org.gradle.api.internal.file.DefaultFileCollectionFactory$ResolvingFileCollection.visitChildren(DefaultFileCollectionFactory.java:285)
2026-05-17T18:44:33.1543048Z em org.gradle.api.internal.file.CompositeFileCollection.visitContents(CompositeFileCollection.java:113)
2026-05-17T18:44:33.1543911Z em org.gradle.api.internal.file.AbstractFileCollection.visitStructure(AbstractFileCollection.java:361)
2026-05-17T18:44:33.1544816Z em org.gradle.api.internal.file.CompositeFileCollection.lambda$visitContents$0(CompositeFileCollection.java:113)
2026-05-17T18:44:33.1545700Z em org.gradle.api.internal.tasks.PropertyFileCollection.visitChildren(PropertyFileCollection.java:48)
2026-05-17T18:44:33.1546553Z em org.gradle.api.internal.file.CompositeFileCollection.visitContents(CompositeFileCollection.java:113)
2026-05-17T18:44:33.1547408Z em org.gradle.api.internal.file.AbstractFileCollection.visitStructure(AbstractFileCollection.java:361)
2026-05-17T18:44:33.1548396Z em org.gradle.internal.fingerprint.impl.DefaultFileCollectionSnapshotter.snapshot(DefaultFileCollectionSnapshotter.java:47)
2026-05-17T18:44:33.1549556Z em org.gradle.internal.execution.impl.DefaultInputFingerprinter$InputCollectingVisitor.visitInputFileProperty(DefaultInputFingerprinter.java:133)
2026-05-17T18:44:33.1550779Z em org.gradle.api.internal.tasks.execution.TaskExecution.visitRegularInputs(TaskExecution.java:327)
2026-05-17T18:44:33.1551772Z em org.gradle.internal.execution.impl.DefaultInputFingerprinter.fingerprintInputProperties(DefaultInputFingerprinter.java:63)
2026-05-17T18:44:33.1553105Z em org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.captureExecutionStateWithOutputs(AbstractCaptureStateBeforeExecutionStep.java:109)
2026-05-17T18:44:33.1554567Z em org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.lambda$captureExecutionState$0(AbstractCaptureStateBeforeExecutionStep.java:74)
2026-05-17T18:44:33.1555723Z em org.gradle.internal.execution.steps.BuildOperationStep$1.call(BuildOperationStep.java:37)
2026-05-17T18:44:33.1556771Z em org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-05-17T18:44:33.1558103Z em org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-05-17T18:44:33.1559131Z em org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-05-17T18:44:33.1560039Z em org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-05-17T18:44:33.1561397Z em org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-05-17T18:44:33.1562309Z em org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-05-17T18:44:33.1563403Z em org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-05-17T18:44:33.1564489Z em org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-05-17T18:44:33.1565341Z em org.gradle.internal.execution.steps.BuildOperationStep.operation(BuildOperationStep.java:34)
2026-05-17T18:44:33.1566462Z em org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.captureExecutionState(AbstractCaptureStateBeforeExecutionStep.java:69)
2026-05-17T18:44:33.1567851Z em org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.execute(AbstractCaptureStateBeforeExecutionStep.java:62)
2026-05-17T18:44:33.1569040Z em org.gradle.internal.execution.steps.AbstractCaptureStateBeforeExecutionStep.execute(AbstractCaptureStateBeforeExecutionStep.java:43)
2026-05-17T18:44:33.1570201Z em org.gradle.internal.execution.steps.AbstractSkipEmptyWorkStep.executeWithNonEmptySources(AbstractSkipEmptyWorkStep.java:125)
2026-05-17T18:44:33.1571415Z em org.gradle.internal.execution.steps.AbstractSkipEmptyWorkStep.execute(AbstractSkipEmptyWorkStep.java:56)
2026-05-17T18:44:33.1572320Z em org.gradle.internal.execution.steps.AbstractSkipEmptyWorkStep.execute(AbstractSkipEmptyWorkStep.java:36)
2026-05-17T18:44:33.1573374Z em org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsStartedStep.execute(MarkSnapshottingInputsStartedStep.java:38)
2026-05-17T18:44:33.1574451Z em org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:36)
2026-05-17T18:44:33.1575464Z em org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:23)
2026-05-17T18:44:33.1576392Z em org.gradle.internal.execution.steps.HandleStaleOutputsStep.execute(HandleStaleOutputsStep.java:75)
2026-05-17T18:44:33.1577241Z em org.gradle.internal.execution.steps.HandleStaleOutputsStep.execute(HandleStaleOutputsStep.java:41)
2026-05-17T18:44:33.1578169Z em org.gradle.internal.execution.steps.AssignMutableWorkspaceStep.lambda$execute$0(AssignMutableWorkspaceStep.java:35)
2026-05-17T18:44:33.1579030Z em org.gradle.api.internal.tasks.execution.TaskExecution$4.withWorkspace(TaskExecution.java:292)
2026-05-17T18:44:33.1579878Z em org.gradle.internal.execution.steps.AssignMutableWorkspaceStep.execute(AssignMutableWorkspaceStep.java:31)
2026-05-17T18:44:33.1580856Z em org.gradle.internal.execution.steps.AssignMutableWorkspaceStep.execute(AssignMutableWorkspaceStep.java:22)
2026-05-17T18:44:33.1581694Z em org.gradle.internal.execution.steps.ChoosePipelineStep.execute(ChoosePipelineStep.java:40)
2026-05-17T18:44:33.1582467Z em org.gradle.internal.execution.steps.ChoosePipelineStep.execute(ChoosePipelineStep.java:23)
2026-05-17T18:44:33.1583474Z em org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.lambda$execute$2(ExecuteWorkBuildOperationFiringStep.java:66)
2026-05-17T18:44:33.1584621Z em org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:66)
2026-05-17T18:44:33.1585734Z em org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:38)
2026-05-17T18:44:33.1586737Z em org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:36)
2026-05-17T18:44:33.1587488Z em org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:26)
2026-05-17T18:44:33.1588186Z em org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:47)
2026-05-17T18:44:33.1588852Z em org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:34)
2026-05-17T18:44:33.1589626Z em org.gradle.internal.execution.impl.DefaultExecutionEngine$1.execute(DefaultExecutionEngine.java:61)
2026-05-17T18:44:33.1590689Z em org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:145)
2026-05-17T18:44:33.1591686Z em org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-05-17T18:44:33.1592722Z em org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-05-17T18:44:33.1593790Z em org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-05-17T18:44:33.1594836Z em org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-05-17T18:44:33.1595836Z em org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-05-17T18:44:33.1596767Z em org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-05-17T18:44:33.1597718Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-05-17T18:44:33.1598611Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-05-17T18:44:33.1599489Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-05-17T18:44:33.1600686Z em org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-05-17T18:44:33.1601836Z em org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-05-17T18:44:33.1602834Z em org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-05-17T18:44:33.1603730Z em org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-05-17T18:44:33.1604627Z em org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-05-17T18:44:33.1605518Z em org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-05-17T18:44:33.1606391Z em org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-05-17T18:44:33.1607289Z em org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-05-17T18:44:33.1608198Z em org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-05-17T18:44:33.1608999Z em org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-05-17T18:44:33.1609932Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-05-17T18:44:33.1611064Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-05-17T18:44:33.1612233Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-05-17T18:44:33.1613219Z em org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-05-17T18:44:33.1614313Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-05-17T18:44:33.1615477Z em org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-05-17T18:44:33.1616443Z em org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-05-17T18:44:33.1617251Z em org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-05-17T18:44:33.1618066Z em org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-05-17T18:44:33.1618895Z em org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-05-17T18:44:33.1619896Z Causado por: org.gradle.internal.resolve.ModuleVersionNotFoundException: Não foi possível encontrar com.getcapacitor:capacitor-android:6.1.2.
2026-05-17T18:44:33.1620745Z Pesquisado nos seguintes locais:
2026-05-17T18:44:33.1621392Z - https://dl.google.com/dl/android/maven2/com/getcapacitor/capacitor-android/6.1.2/capacitor-android-6.1.2.pom
2026-05-17T18:44:33.1622251Z - https://repo.maven.apache.org/maven2/com/getcapacitor/capacitor-android/6.1.2/capacitor-android-6.1.2.pom
2026-05-17T18:44:33.1622712Z Requerido por:
2026-05-17T18:44:33.1622982Z projeto :app
2026-05-17T18:44:33.1623096Z
2026-05-17T18:44:33.1623116Z
2026-05-17T18:44:33.1623228Z FALHA NA COMPILAÇÃO em 22s
2026-05-17T18:44:33.1623493Z 2 tarefas executáveis: 2 executadas
2026-05-17T18:44:33.1643228Z ##[group]Executar find android -name "*.apk" | head -5
2026-05-17T18:44:33.1643566Z [36;1mfind android -name "*.apk" | head -5 [0m
2026-05-17T18:44:33.1673088Z shell: /usr/bin/bash -e {0}
2026-05-17T18:44:33.1673490Z env:
2026-05-17T18:44:33.1673988Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:44:33.1674844Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:44:33.1675519Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:44:33.1675968Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:44:33.1676369Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:44:33.1677045Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:44:33.1677870Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:44:33.1678354Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:44:33.1678840Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:44:33.1679298Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:44:33.1679734Z ##[endgroup]
2026-05-17T18:44:33.1791042Z ##[group]Executar ações/upload-artefato@v4
2026-05-17T18:44:33.1791302Z com:
2026-05-17T18:44:33.1791523Z nome: sk-code-editor-v4-web-1-android-debug-apk
2026-05-17T18:44:33.1791849Z caminho: android/app/build/outputs/apk/debug/app-debug.apk
2026-05-17T18:44:33.1792138Z dias de retenção: 30
2026-05-17T18:44:33.1792330Z if-no-files-found: aviso
2026-05-17T18:44:33.1792521Z nível de compressão: 6
2026-05-17T18:44:33.1792704Z sobrescrever: falso
2026-05-17T18:44:33.1792879Z incluir-arquivos-ocultos: falso
2026-05-17T18:44:33.1793085Z env:
2026-05-17T18:44:33.1793344Z JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:44:33.1793772Z JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.19-10/x64
2026-05-17T18:44:33.1794141Z GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-05-17T18:44:33.1794403Z GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-05-17T18:44:33.1794656Z GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-05-17T18:44:33.1795065Z DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-05-17T18:44:33.1795494Z DEVELOCITY_AUTO_INJECTION_CUSTOM_VALUE: gradle-actions
2026-05-17T18:44:33.1795784Z GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-05-17T18:44:33.1796152Z ANDROID_HOME: /usr/local/lib/android/sdk
2026-05-17T18:44:33.1796405Z ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-05-17T18:44:33.1796643Z ##[endgroup]
2026-05-17T18:44:33.3837795Z ##[aviso]Nenhum arquivo foi encontrado no caminho fornecido: android/app/build/outputs/apk/debug/app-debug.apk. Nenhum artefato será enviado.
2026-05-17T18:44:33.3948767Z Limpeza pós-trabalho.
2026-05-17T18:44:33.5622512Z Limpeza pós-trabalho.
2026-05-17T18:44:33.7918943Z Na etapa pós-ação
2026-05-17T18:44:33.7928186Z Parando todos os daemons do Gradle antes de salvar o estado do diretório inicial do usuário do Gradle.
2026-05-17T18:44:33.7929348Z Parando os daemons do Gradle para /home/runner/gradle-installations/installs/gradle-8.6
2026-05-17T18:44:33.7939016Z Parando os daemons do Gradle para /home/runner/.gradle/wrapper/dists/gradle-8.6-bin/afr5mpiioh2wthjmwnkmdsd5w/gradle-8.6
2026-05-17T18:44:33.7946001Z [comando]/home/runner/gradle-installations/installs/gradle-8.6/bin/gradle --stop
2026-05-17T18:44:33.7982860Z [comando]/home/runner/.gradle/wrapper/dists/gradle-8.6-bin/afr5mpiioh2wthjmwnkmdsd5w/gradle-8.6/bin/gradle --stop
2026-05-17T18:44:35.0620776Z Parando o(s) daemon(s)
2026-05-17T18:44:35.0642185Z Parando o(s) daemon(s)
2026-05-17T18:44:35.0790033Z 1 Daemon parado
2026-05-17T18:44:35.0805329Z 1 Daemon parado
2026-05-17T18:44:35.0884944Z ##[group]Caching Gradle state
2026-05-17T18:44:35.1064521Z Armazenando em cache o wrapper-zips com o caminho '/home/runner/.gradle/wrapper/dists/gradle-8.6-bin/afr5mpiioh2wthjmwnkmdsd5w' e a chave de cache: gradle-wrapper-zips-v1-61c267d33d913e95c956e860b86f9705
2026-05-17T18:44:35.1189590Z [comando]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android --files-from manifest.txt --use-compress-program zstdmt
2026-05-17T18:44:35.3674039Z Armazenando em cache as dependências com o caminho '/home/runner/.gradle/caches/modules-*/files-*/*/*/*/*' e a chave de cache: gradle-dependencies-v1-a26f13d6ab3903e5a3a17b60638d1c8e
2026-05-17T18:44:35.3784626Z Armazenando em cache os jars instrumentados com o caminho '/home/runner/.gradle/caches/jars-*/*/' e a chave de cache: gradle-instrumented-jars-v1-7e2ae11afdac2c21758077edd858c98b
2026-05-17T18:44:35.4024133Z [comando]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android --files-from manifest.txt --use-compress-program zstdmt
2026-05-17T18:44:35.5058039Z Armazenando em cache as transformações com o caminho '/home/runner/.gradle/caches/transforms-4/*/
2026-05-17T18:44:35.5059492Z /home/runner/.gradle/caches/*/transforms/*/' e chave de cache: gradle-transforms-v1-73a0790e047fe088abcf4fdeffa08090
2026-05-17T18:44:35.5383008Z ##[aviso]Falha ao salvar a entrada de cache com o caminho '/home/runner/.gradle/caches/jars-*/*/' e a chave: gradle-instrumented-jars-v1-7e2ae11afdac2c21758077edd858c98b: Erro: <h2>Nossos serviços não estão disponíveis no momento</h2><p>Estamos trabalhando para restaurar todos os serviços o mais rápido possível. Volte em breve.</p>0kwwKagAAAADZwiNJjHKoRIbvuS6o+MvKU0xDMzFFREdFMDIxOABFZGdl
2026-05-17T18:44:35.5899202Z [comando]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android --files-from manifest.txt --use-compress-program zstdmt
2026-05-17T18:44:35.7393974Z [comando]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android --files-from manifest.txt --use-compress-program zstdmt
2026-05-17T18:44:35.8078431Z ##[aviso]Falha ao salvar a entrada de cache com o caminho '/home/runner/.gradle/wrapper/dists/gradle-8.6-bin/afr5mpiioh2wthjmwnkmdsd5w' e a chave: gradle-wrapper-zips-v1-61c267d33d913e95c956e860b86f9705: Erro: <h2>Nossos serviços não estão disponíveis no momento</h2><p>Estamos trabalhando para restaurar todos os serviços o mais rápido possível. Volte em breve.</p>0kwwKagAAAAAhtoJSLS8JQpCYhLCTMLh2U0xDMzFFREdFMDExNABFZGdl
2026-05-17T18:44:36.5731825Z ##[aviso]Falha ao salvar a entrada de cache com o caminho '/home/runner/.gradle/caches/modules-*/files-*/*/*/*/*' e a chave: gradle-dependencies-v1-a26f13d6ab3903e5a3a17b60638d1c8e: Erro: <h2>Nossos serviços não estão disponíveis no momento</h2><p>Estamos trabalhando para restaurar todos os serviços o mais rápido possível. Volte em breve.</p>0lAwKagAAAACBJcriCqovT6DkYAtbLJjfU0xDMzFFREdFMDIxNwBFZGdl
2026-05-17T18:44:36.9425858Z ##[aviso]Falha ao salvar a entrada de cache com o caminho '/home/runner/.gradle/caches/transforms-4/*/
/home/runner/.gradle/caches/*/transforms/*/' e chave: gradle-transforms-v1-73a0790e047fe088abcf4fdeffa08090: Erro: <h2>Nossos serviços não estão disponíveis no momento</h2><p>Estamos trabalhando para restaurar todos os serviços o mais rápido possível. Por favor, volte em breve.</p>0lAwKagAAAABboDBFnbdsS6AUt935/oz8U0xDMzFFREdFMDExNABFZGdl
2026-05-17T18:44:37.0102950Z Armazenando em cache o diretório inicial do usuário Gradle com a chave de cache: gradle-home-v1|Linux|build[e080f0fdc288b6f0c5023fd4b86f7a10]-27f1ece1b43ecb530dc262cb14bbb9d278eaa267
2026-05-17T18:44:37.0182396Z [comando]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android --files-from manifest.txt --use-compress-program zstdmt
2026-05-17T18:44:37.1419696Z ##[aviso]Falha ao salvar a entrada de cache com o caminho '/home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle' e a chave: gradle-home-v1|Linux|build[e080f0fdc288b6f0c5023fd4b86f7a10]-27f1ece1b43ecb530dc262cb14bbb9d278eaa267: Erro: <h2>Nossos serviços não estão disponíveis no momento</h2><p>Estamos trabalhando para restaurar todos os serviços o mais rápido possível. Volte em breve.</p>0lQwKagAAAADSnUJ83cduT5rJsObzJc9oU0xDMzFFREdFMDIxNABFZGdl
2026-05-17T18:44:37.1424135Z ##[endgroup]
2026-05-17T18:44:37.1424697Z Gerando Resumo do Trabalho
2026-05-17T18:44:37.1438500Z Etapa pós-ação concluída
2026-05-17T18:44:37.1571213Z Limpeza pós-trabalho.
2026-05-17T18:44:37.3237445Z Limpeza pós-trabalho.
2026-05-17T18:44:37.4145616Z [comando]/usr/bin/git versão
2026-05-17T18:44:37.4177908Z versão do git 2.54.0
2026-05-17T18:44:37.4217899Z Substituindo temporariamente HOME='/home/runner/work/_temp/97281d3f-303c-4a45-88cf-ca6228f1dabd' antes de fazer alterações globais na configuração do git
2026-05-17T18:44:37.4219480Z Adicionando o diretório do repositório à configuração global temporária do Git como um diretório seguro.
2026-05-17T18:44:37.4234594Z [comando]/usr/bin/git config --global --add safe.directory /home/runner/work/sk-code-editor-v4-web-1-android-android/sk-code-editor-v4-web-1-android-android
2026-05-17T18:44:37.4270095Z [comando]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-05-17T18:44:37.4304561Z [comando]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-05-17T18:44:37.4479507Z [comando]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-05-17T18:44:37.4500545Z http.https://github.com/.extraheader
2026-05-17T18:44:37.4510880Z [comando]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2026-05-17T18:44:37.4535332Z [comando]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-05-17T18:44:37.4703414Z [comando]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-05-17T18:44:37.4729339Z [comando]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-05-17T18:44:37.4993769Z Limpando processos órfãos
2026-05-17T18:44:37.5196754Z ##[aviso]As ações do Node.js 20 estão obsoletas. As seguintes ações estão sendo executadas no Node.js 20 e podem não funcionar como esperado: actions/checkout@v4, actions/setup-java@v4, actions/setup-node@v4, actions/upload-artifact@v4, android-actions/setup-android@v3, gradle/actions/setup-gradle@v3. A partir de 2 de junho de 2026, as ações serão executadas com o Node.js 24 por padrão. O Node.js 20 será removido do executor em 16 de setembro de 2026. Verifique se existem versões atualizadas dessas ações que suportam o Node.js 24. Para optar pelo Node.js 24 agora, defina a variável de ambiente FORCE_JAVASCRIPT_ACTIONS_TO_NODE24=true no executor ou no seu arquivo de fluxo de trabalho. Assim que o Node.js 24 se tornar o padrão, você poderá desativá-lo temporariamente definindo ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true. Para mais informações, consulte: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/