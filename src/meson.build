capp_sources = [
  'gstpcapparse.c',
  'gstirtspparse.c',
  'plugin.c',
]

gstpcapparse = library('gstpcapparse',
  capp_sources,
  c_args : gst_plugins_bad_args,
#  include_directories : [configinc],
  dependencies : [gstbase_dep],
)
