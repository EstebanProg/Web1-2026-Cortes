# Declaración de uso de IA

> Obligatoria en todas las prácticas. Si usaste un asistente, descríbelo aquí con
> precisión. Si NO usaste ninguno, escribe eso y explica cómo resolviste la parte
> más difícil por tu cuenta — también cuenta como declaración válida.
>
> Recuerda: código de IA sin declarar se califica en CERO y no admite reintento.
> Declararlo honestamente NO baja tu nota. Lo que se evalúa es tu capacidad de auditar.

## Herramientas que usé
<!-- Ej.: GitHub Copilot en VS Code, ChatGPT, Claude, Cursor. Indica también si no usaste ninguna. -->
Se utilizo la IA de Claude para revisar errores en el html


## Qué le pedí
<!-- Escribe el prompt real, no un resumen idealizado -->

``` obtuve unos errores pequeños de los cuales no pude solucionar, necesito una solución rapida para las consultas que estan mal en el html indicame cuales son yo los cambio manualmente
```

## Qué me devolvió
<!-- Pega el fragmento relevante -->
Son errores del validador de HTML (probablemente HTMLHint o similar corriendo en tu GitHub Action). Aquí está qué significa cada uno y cómo arreglarlo:
```javascript
```

## Qué estaba mal
<!-- La parte más importante del documento. Sé específico: qué falla, en qué caso,
     por qué el código parecía correcto pero no lo era. Si de verdad no encontraste
     ningún error, explica cómo lo verificaste (qué casos probaste). -->

     Pues estaba bien realmente eran cosas de etiquetas como un type"submit" y asi mas que por el codigo como tal

## Qué corregí y por qué
<!-- Tu código final y el razonamiento del cambio -->
Solo el submit

```javascript
<form>
  <button type="submit">Enviar</button>
</form>
```

## Qué escribí yo desde cero
<!-- Qué partes no delegaste, y por qué decidiste no delegarlas -->
Casi todo el codigo, no las delegue porque estaban bien construidas solo agregue el submit y ya

## Reflexión
<!-- ¿Te ahorró tiempo de verdad, o lo perdiste depurando? ¿Volverías a usarlo para esto? -->
Realmente me ayudo a identifacar el error en la etiqueta y ya eso fue todo
