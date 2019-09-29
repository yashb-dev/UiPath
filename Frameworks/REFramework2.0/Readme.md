# REFramework2.0

V1.0.2
- Added Credentials sheet in Config.xlsx
  - Added flow to get credentials and add to out_Config using Name + "_username" or "_password" as keys
- Added environment startup parameter
  - used to determine which assets are retrieved from orchestrator, which queue is used, as well as which process is used
- Added switch to Process.xaml based on environment startup parameter that determines which process to use (added Process_DEV, Process_TEST, Process_UAT, Process_PROD xamls to Framework)
  - Default is throw system exception
