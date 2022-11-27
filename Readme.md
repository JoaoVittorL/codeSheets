### Excel testes

Pegar o periodo que deseja:

```
     =CONT.SES(FILTER(INDIRETO(A2&"!A1:G");INDIRETO(A2&"!A:A")>=$E$2;INDIRETO(A2&"!A:A")<=$F$2);"Motorista não identificado...")
```

Pegar a cidade:

```
  =PROCV($E$2;INDIRETO(A2&"!A1:K");9;0)

```

Analisa a quantidae de não identificados

```
   =SE(D2 > 7; "Analisar"; "ok")

```
