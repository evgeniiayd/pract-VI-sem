#!/bin/bash

sudo echo "
text/csv=r7-office-desktopeditors.desktop
text/docxf=r7-office-desktopeditors.desktop
application/rtf=r7-office-desktopeditors.desktop
application/pdf=org.kde.okular.desktop
image/vnd.djvu=r7-office-desktopeditors.desktop
text/oform=r7-office-desktopeditors.desktop
application/msword=r7-office-text.desktop
application/vnd.openxmlformats-officedocument.wordprocessingml.document=r7-office-text.desktop
application/vnd.openxmlformats-officedocument.wordprocessingml.template=r7-office-text.desktop
application/vnd.ms-word.document.macroEnabled.12=r7-office-text.desktop
application/vnd.ms-word.template.macroEnabled.12=r7-office-text.desktop
application/vnd.ms-excel=r7-office-table.desktop
application/vnd.openxmlformats-officedocument.spreadsheetml.sheet=r7-office-table.desktop
application/vnd.openxmlformats-officedocument.spreadsheetml.template=r7-office-table.desktop
application/vnd.ms-excel.sheet.macroEnabled.12=r7-office-table.desktop
application/vnd.ms-excel.template.macroEnabled.12=r7-office-table.desktop
application/vnd.ms-excel.addin.macroEnabled.12=r7-office-table.desktop
application/vnd.ms-excel.sheet.binary.macroEnabled.12=r7-office-table.desktop
application/vnd.ms-powerpoint=r7-office-presentation.desktop
application/vnd.openxmlformats-officedocument.presentationml.presentation=r7-office-presentation.desktop
application/vnd.openxmlformats-officedocument.presentationml.template=r7-office-presentation.desktop
application/vnd.openxmlformats-officedocument.presentationml.slideshow=r7-office-presentation.desktop
application/vnd.ms-powerpoint.addin.macroEnabled.12=r7-office-presentation.desktop
application/vnd.ms-powerpoint.presentation.macroEnabled.12=r7-office-presentation.desktop
application/vnd.ms-powerpoint.template.macroEnabled.12=r7-office-presentation.desktop
application/vnd.ms-powerpoint.slideshow.macroEnabled.12=r7-office-presentation.desktop
application/vnd.oasis.opendocument.presentation=libreoffice-impress
application/vnd.oasis.opendocument.spreadsheet=libreoffice-writer
application/vnd.oasis.opendocument.text=libreoffice-calc
application/vnd.ms-xpsdocument=r7-office-desktopeditors.desktop
" >> /usr/share/applications/mimeapps.list

printf "\e[32mDONE\e[0m\n"
