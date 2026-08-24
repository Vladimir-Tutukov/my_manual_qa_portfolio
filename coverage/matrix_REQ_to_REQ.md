| Module | Req ID | Summary | Dependencies | Impact on Other Modules |
| main | REQ-main-001 | Погода на главной странице | - | search, map, menu |
| main | REQ-main-002 | Дополнительные инструменты на главной странице | - | search, map, menu |
| search | REQ-search-003 | Поиск локации через поисковую строку | main | - |
| search | REQ-search-004 | Поиск локации через футер сайта | main | - |
| menu | REQ-menu-005 | Меню мобильной версии | main | map |
| menu | REQ-menu-006 | Меню десктопной версии | main | map |
| map | REQ-map-007 | Карта осадков | main, menu | - |
| map | REQ-map-008 | Карта температуры | main, menu | REQ-map-009 |
| map | REQ-map-009 | Карта ветра | main, menu, REQ-map-008 | - |
| map | REQ-map-010 | карта давления | main, menu | - |