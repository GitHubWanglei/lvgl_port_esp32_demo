# lvgl_port_esp32_demo
This esp32 project demo has integrated lvgl and ili9488 display drivers, you can compile directly and run it without any other configuration! 

  
The project used VSCode ide, so you should install `ESP-IDF` extensition firstly in the VSCode.  

<img src="https://github.com/GitHubWanglei/lvgl_port_esp32_demo/assets/16434720/fc1099ea-05b8-41cd-8b4c-553127f03a09" width="400"/>

# Usage
#### 1. The project folder is `sample_project`, so you should use VSCode open the `sample_project`.
#### 2. In the VSCode, select USB port which your esp32 board connected.
#### 3. Set espressif device target.
#### 4. Build the project directly.
When you build the project, the projcet will download `lvgl` and `ili9488` library firstly, download infomation is in the `idf_component.yml`:
```yml
## IDF Component Manager Manifest File
dependencies:
  bienxanh1901/esp_lvgl_port: "^1.4.0"
  atanisoft/esp_lcd_ili9488: "^1.0.9"
  ## Required IDF version
  idf:
    version: ">=4.1.0"
```
#### 5. Flash to you esp32 board.
