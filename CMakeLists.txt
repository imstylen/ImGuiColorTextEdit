project(ImGuiColorTextEdit)


add_library(ImGuiColorTextEdit
        "src/TextEditor.h"
        "src/TextEditor.cpp"
)

target_link_libraries(ImGuiColorTextEdit PRIVATE imgui)

target_include_directories(ImGuiColorTextEdit PUBLIC src)