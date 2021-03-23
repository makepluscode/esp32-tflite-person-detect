
#
# Main component of TF Micro project 'person_detection_int8'.
#

idf_component_register(SRCS
    ./src/detection_responder.cc
    ./src/image_provider.cc
    ./src/main.cc
    ./src/main_functions.cc
    ./src/model_settings.cc
    INCLUDE_DIRS ""
)
