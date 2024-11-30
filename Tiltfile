# Build and run the wiki application
local_resource(
    'wiki',
    cmd='go build wiki.go',
    serve_cmd='./wiki',
    deps=['wiki.go', 'tmpl/'],
    labels=['go']
)

# Add live reload for template files
watch_file('tmpl/')
