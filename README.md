# onevpl_gstreamer

Demonstrates building GStreamer top of tree with latest cartwheel patches to enable oneVPL support from oneAPI
 
See https://software.intel.com/content/www/us/en/develop/articles/oneapi-repo-instructions.html and https://github.com/intel-media-ci/cartwheel-gst-plugins-bad for more details

## To run

The following command will build the dockerfile

```bash
$ ./build.sh
```

The following command will run a sample VAAPI plugin

```bash
$ ./run_vaapi.sh
```

The following command will run a sample VAAPI plugin

```bash
$ ./run_vpl.sh
```
