Используйте `debounce`, чтобы оптимизировать операции, которые можно выполнить единожды в конце.

Например, для формы поиска это подойдёт. Однако для отслеживания движения мыши — нет, потому что будет странно ждать, пока пользователь остановит курсор.

Для таких задач, которые можно выполнять _раз в какое-то количество времени_, лучше подходит [`throttle`](/js/throttle).
