# Color Match — versão de teste (RZN Films)

Gerador de LUT: você escolhe uma imagem sua e uma referência de cor, e o app gera um `.cube` para usar no DaVinci Resolve (ou qualquer editor).

## Baixar
Baixe o arquivo `ColorMatch-teste.dmg` em **[Instalador](../../releases/tag/instalador)**. Só precisa baixar uma vez: depois o app se atualiza sozinho ao abrir (aparece um botão "Nova versão · Reiniciar").

## Instalar (Mac com chip Apple: M1, M2, M3...)
1. Abra o `.dmg` e arraste **Color Match** para a pasta **Aplicativos**.
2. O app não é assinado pela Apple, então o Mac bloqueia na primeira vez. Abra o **Terminal** e cole:

```
xattr -cr "/Applications/Color Match.app"
```

3. Abra o Color Match normalmente. (Alternativa: botão direito no app > Abrir > Abrir.)

Não precisa ter o DaVinci Resolve instalado. **Não funciona em Mac Intel.**

## Como testar
Carregue sua imagem e uma referência, gere a LUT e salve o `.cube`. Se algo travar, ficar lento ou estranho, mande um print.
