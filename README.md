# Command-sequences
Command sequences for setting up blank projects quickly (windows)

# Vue.js

vue create --default my-custom-project & cd my-custom-project & del /s /q src\components\*.* & del /f /q src\App.vue & type nul > src\App.vue

# Vue.js + Server

vue create --default my-custom-project & cd my-custom-project & del /s /q src\components\*.* & del /f /q src\App.vue & type nul > src\App.vue & cd .. & mkdir server & cd server & type nul > server.js
