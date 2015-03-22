
FILE(GLOB datafiles *.kvtml)
install( FILES ${datafiles} DESTINATION  ${KDE_INSTALL_DATADIR}/apps/kvtml/en )
add_custom_target( kvtml_data )

