project('pcapzz', 'c',
  version : '1.0.0',
  license : 'MIT')

gst_plugins_bad_args = ['-DHAVE_CONFIG_H']
gst_req = '>= @0@.@1@.0'.format(1, 14)
gstbase_dep = dependency('gstreamer-base-1.0', version : gst_req, fallback : ['gstreamer', 'gst_base_dep'])

subdir('src')
#capp_sources = [
#  'gstpcapparse.c',
#  'gstirtspparse.c',
#  'plugin.c',
#]
#
#gstpcapparse = library('gstpcapparse',
#  capp_sources,
#  c_args : gst_plugins_bad_args,
#  include_directories : [configinc],
#  dependencies : [gstbase_dep] + winsock2,
#)
