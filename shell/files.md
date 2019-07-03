### recursively delete all node_modules

`find . -name 'node_modules' -type d -prune` show them

`find . -name node_modules -type d -prune -exec trash {} +` trash them
