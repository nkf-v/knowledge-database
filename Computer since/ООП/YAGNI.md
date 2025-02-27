__YAGNI - Вам это не понадобится (You aren't gonna need it)__

Процесс и принцип проектирования ПО, при котором в качестве основной цели и/или ценности декларируется отказ от избыточной функциональности, — то есть отказ добавления функциональности, в которой нет непосредственной надобности.

Согласно адептам принципа YAGNI, желание писать код, который не нужен прямо сейчас, но может понадобиться в будущем, приводит к следующим нежелательным последствиям:

- Тратится время, которое было бы затрачено на добавление, тестирование и улучшение необходимой функциональности.
- Новые функции должны быть отлажены, документированы и сопровождаться.
- Новая функциональность ограничивает то, что может быть сделано в будущем, — ненужные новые функции могут впоследствии помешать добавить новые нужные.
- Пока новые функции действительно не нужны, трудно полностью предугадать, что они должны делать, и протестировать их. Если новые функции тщательно не протестированы, они могут неправильно работать, когда впоследствии понадобятся.
- Это приводит к тому, что программное обеспечение становится более сложным (подчас чрезмерно сложным).
- Если вся функциональность не документирована, она может так и остаться неизвестной пользователям, но может создать различные риски для безопасности пользовательской системы.
- Добавление новой функциональности может привести к желанию ещё более новой функциональности, приводя к эффекту «снежного кома».