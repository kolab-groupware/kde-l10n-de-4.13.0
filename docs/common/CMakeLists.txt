FILE(GLOB _html *.html)
FILE(GLOB _css *.css)
FILE(GLOB _pngs *.png)
install( FILES ${_html} ${_css} ${_png} DESTINATION ${HTML_INSTALL_DIR}/${CURRENT_LANG}/common)
