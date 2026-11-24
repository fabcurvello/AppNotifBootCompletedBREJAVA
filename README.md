# App Notificação ao Reiniciar (BRE, Java)

> Repositório didático: exercício prático de Android nativo com **Java**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Aplicativo que mostra uma **notificação quando o aparelho é reiniciado**, usando um Broadcast Receiver registrado no Manifest.

## Contexto acadêmico

Exercício aplicado em sala de aula, usado como prática guiada com os alunos.

## Versão em Kotlin

Esta mesma aplicação também foi desenvolvida em **Kotlin**: [AppNotifBootCompletedBREKotlin](https://github.com/fabcurvello/AppNotifBootCompletedBREKotlin). Comparar as duas versões lado a lado ajuda a entender as diferenças de sintaxe entre Java e Kotlin no Android.

## O que o app faz

- A classe `BootBroadcastReceiver`, declarada no `AndroidManifest.xml`, recebe o evento `ACTION_BOOT_COMPLETED`.
- Quando o aparelho termina de ligar, o app cria um canal de notificação e mostra a notificação "Dispositivo Inicializado".

## Conceitos trabalhados em aula

- `BroadcastReceiver` registrado **estaticamente** no Manifest (BRE)
- Permissões `RECEIVE_BOOT_COMPLETED` e `POST_NOTIFICATIONS`
- Notificações com `NotificationChannel` e `NotificationCompat`
- Diferença entre receivers estáticos e dinâmicos

## Tecnologias

- **Java**
- **Android SDK** (Android Studio)
- **Gradle**
- `minSdk 28` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/AppNotifBootCompletedBREJAVA.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 28 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [AppBroadcastReceiversJava](https://github.com/fabcurvello/AppBroadcastReceiversJava)
- [AppDetectBatteryLowDBRJava](https://github.com/fabcurvello/AppDetectBatteryLowDBRJava)
- [AppDetectBatteryLowDBRKotlin](https://github.com/fabcurvello/AppDetectBatteryLowDBRKotlin)
- [AppDetectChargeDBRJava](https://github.com/fabcurvello/AppDetectChargeDBRJava)
- [AppDetectChargeDBRKotlin](https://github.com/fabcurvello/AppDetectChargeDBRKotlin)
- [AppNotifBateryLevelBRDJava](https://github.com/fabcurvello/AppNotifBateryLevelBRDJava)
- [AppNotifBateryLevelBRDKotlin](https://github.com/fabcurvello/AppNotifBateryLevelBRDKotlin)
- [AppNotifBootCompletedBREKotlin](https://github.com/fabcurvello/AppNotifBootCompletedBREKotlin)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
