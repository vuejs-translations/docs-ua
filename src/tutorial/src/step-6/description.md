# Умовний рендеринг {#conditional-rendering}

Ми можемо використовувати `v-if` директиву для умовного рендерингу елемента:

```vue-html
<h1 v-if="awesome">Vue - це круто!</h1>
```

Цей елемент `<h1>` буде згенеровано лише якщо значення `awesome` є [правдивим](https://developer.mozilla.org/en-US/docs/Glossary/Truthy). Якщо ж `awesome` змінюється на [неправдиве значення](https://developer.mozilla.org/en-US/docs/Glossary/Falsy), тоді цей елемент буде видалено з DOM.

Також можливо використовувати `v-else` та `v-else-if`, щоб вказати альтернативні варіанти умови:

```vue-html
<h1 v-if="awesome">Vue - це круто!</h1>
<h1 v-else>Ой, ні 😢</h1>
```

Наразі, демо показує обидва елементи `<h1>` одночасно, і кнопка нічого не робить. Спробуйте додати директиви `v-if` та `v-else` і напишіть метод `toggle()` таким чином, щоб кнопка перемикала ці елементи.

Більш детально про `v-if` в <a target="_blank" href="/guide/essentials/conditional.html">гіді про умовний рендеринг</a>.
