#
# tensorflow lite micro example
#

set(SRC_FILES
    "./src/main.cc"
    "./src/camera/app_camera_esp.cc"
    "./src/camera/image_provider.cc"
    "./src/inference/detection_responder.cc"
    "./src/inference/main_functions.cc"
    "./src/inference/model_settings.cc"
)

set(INC_DIRS
    "."
    "./src/camera"
    "./src/inference"
    "../components/esp32-camera/driver/include"
)

idf_component_register(
    SRCS           "${SRC_FILES}"
    INCLUDE_DIRS   "${INC_DIRS}"
)
