set(hdrs WebCamera.h
    PARENT_SCOPE
    ImgSVC_impl.h
    )

install(FILES ${hdrs} DESTINATION ${INC_INSTALL_DIR}/${PROJECT_NAME}
    COMPONENT library)

