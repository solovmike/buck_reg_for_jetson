проект не является отдельной платой и может быть использован только как часть платы

для добавления к себе в проект рекомендуется использовать буфер обмена, но поддерживаются и возможность использовать device sheet symbols и snippets

использование device sheet symbol для схемы:
- скопируйте файл ./project/reuse/device_sheet/buck_reg_12v_6a.SchDoc
- вставьте его в одной из папок указанных в preferences -> data management -> device sheets
- затем на отдельной схеме выполните place -> device sheet symbol

использование snippets для PCB:
- скоприруйте все файлы в папке ./project/reuse/routing_snippet
- вставьте их в папку где altium хранит snippets, обычно это Users\Public\Documents\Altium\AD{ ВАША ВЕРСИЯ }\Examples\Snippets Examples
- перезагрузите altium
- откройте панель design reuse, найдите там routing_for_buck_reg_12v_6a, и нажмите place