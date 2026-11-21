# Touch-Dz.7

Módulo que troca a bolinha do **"Mostrar toques"** do Android pela **espada de diamante do Minecraft** em pixel art.

<p align="center"><img src="screenshots/espada.png" width="160" alt="Espada"></p>

## Download

Baixe o `Touch-Dz.7.zip` na página de [Releases](https://github.com/DevRaphas/Touch-Dz.7/releases/latest).

SHA-256 da v4:

```
47f0b0d39fe55b7e51aade2566130a812dbe5150863f4b0a817bcd80711e2265
```

## Requisitos

- Root ou temp root com suporte a módulos (KernelSU, Magisk, APatch ou AgneSU)
- Android 9 ou superior
- Testado no POCO X7 Pro (HyperOS 3, Android 16). Em outros aparelhos pode funcionar, mas não foi testado.

## Instalação

1. Abra o gerenciador de módulos e instale o `Touch-Dz.7.zip`.
2. Reinicie o celular.
3. Vá em **Configurações → Opções do desenvolvedor → Mostrar toques** e ative.

Para remover, desative ou desinstale o módulo e reinicie.

## Como funciona

O módulo instala um overlay estático (`com.dz7.touch`) em `/product/overlay` que substitui os recursos `pointer_spot_touch_icon` e `pointer_spot_touch_vector_icon` do framework do Android. O código-fonte do overlay está em [`src/`](src).

## Créditos

Criado por **Dz.7**.

Projeto de fã, sem ligação com a Mojang ou a Microsoft. Minecraft é marca registrada da Mojang Studios.
