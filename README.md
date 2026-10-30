# Widget Temperatura

Uma aplicação Android que mantém a temperatura estimada do dispositivo visível num widget flutuante, mesmo enquanto usa outras aplicações.

> **Nota:** a leitura é uma estimativa, não uma medição direta da temperatura da CPU. A app combina a temperatura da bateria, quando disponível, com o estado térmico e a margem térmica disponibilizados pelo Android. O valor apresentado é suavizado para reduzir oscilações.

## ✨ Funcionalidades

- **Widget flutuante:** apresenta a temperatura estimada sobre outras aplicações e permite arrastá-lo para a posição desejada. A posição é guardada.
- **Indicador por cores:** verde abaixo do limite de aviso, amarelo a partir do limite de aviso e vermelho a partir do limite crítico.
- **Limites configuráveis:** ajuste do aviso amarelo e do limite crítico através de controlos deslizantes.
- **Calibração:** aplique um ajuste entre −20 °C e +20 °C à leitura apresentada.
- **Alertas:** escolha entre alertas para ambos os limites, apenas para o limite crítico ou nenhum alerta. O alerta crítico também pode emitir um som.
- **Definições rápidas:** adicione o botão da app ao painel de Definições rápidas para iniciar ou parar a monitorização.
- **Idiomas:** interface disponível em português, inglês, francês e espanhol.
- **Preferências guardadas:** os limites, a calibração, os alertas, o som e o idioma mantêm-se entre utilizações.
- **Acesso rápido às definições:** mantenha o widget pressionado para abrir a aplicação.

## 🚀 Como começar

1. Abra a aplicação e conceda a permissão para **apresentar sobre outras aplicações** quando solicitada.
2. Ative **Monitorização** para iniciar o serviço e mostrar o widget flutuante.
3. Arraste o widget para o local pretendido. A posição fica guardada automaticamente.
4. Ajuste os limites e os alertas nas definições e carregue em **Guardar**.
5. Opcionalmente, adicione o botão **Widget Temp** às Definições rápidas.

No Android 13 ou superior, a app também pode solicitar permissão para notificações. A opção de otimização da bateria abre as definições do sistema para a app; a sua utilização é opcional.

## ⚙️ Definições

| Definição | Valores disponíveis | Predefinição |
|---|---:|---:|
| Aviso amarelo | 30–60 °C | 44 °C |
| Limite crítico vermelho | 50–80 °C | 55 °C |
| Calibração | −20 a +20 °C | 0 °C |
| Modo de alertas | Todos, apenas críticos ou desativados | Todos |
| Som do alerta crítico | Ativado ou desativado | Ativado |
| Idioma | Português, English, Français, Español | Português |

O botão **Repor** restaura as predefinições. As alterações aos limites, à calibração e aos alertas são guardadas com **Guardar**.

## 📱 Requisitos

- Android 8.0 (API 26) ou superior.
- Permissão de sobreposição para apresentar o widget flutuante.
- Permissão de notificações no Android 13 ou superior para receber alertas como notificações.

## 🛠️ Compilar

O projeto usa Kotlin, Jetpack Compose e Gradle. 


