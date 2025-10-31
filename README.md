# home-assistent-marstek
Home Assistent templates and dashboard for Marstek Venus batteries

See https://github.com/whyisthisbroken/Marstek-LilyGo-and-Home-Assistant-Config for original source adjusted to 3 batteries

## Installation

- Create templates folder in HA config
- Copy templates files to this folder
- Update configuration.yaml to include templates from folder
```
template: !include_dir_merge_list templates
```
- Create a new dashboard
- Edit raw yaml for dashboard
- Insert yaml from battery-dashboard.yaml file
