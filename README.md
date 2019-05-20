# Newly generated Panasonic LX100M2 noise profiles

Find `darktable-noiseprofile-20190521.tar.gz` with jpeg thumbnails and pdf graphs as a result of `/opt/darktable/libexec/darktable/tools/darktable-gen-noiseprofile -d ./` script work.

Achieved using the instruction: https://pixls.us/articles/how-to-create-camera-noise-profiles-for-darktable/.

Raw files are generated with Panasonic LX100M2 equipped with Firmware Ver.1.1.
Pictures are taken with Extended ISO is on (range 100-25600 with ISO increment 1/3 EV).

You can find log output below:
```shell
[ddyakov@archlinuxdd2 LX100M2_noise_profiles]$ /opt/darktable/libexec/darktable/tools/darktable-gen-noiseprofile -d ./
===> Check for required tools
--> Check for images handling tools availability
--> Check for images export tools availability
--> Check for profiling tools availability
--> Check for tethering tools availability
--> Check for pdf tools availability

===> Check profiling directory

===> List profiling input RAW images
--> Found ISO 100 image: ./P1001194.RW2
--> Found ISO 125 image: ./P1001195.RW2
--> Found ISO 160 image: ./P1001196.RW2
--> Found ISO 200 image: ./P1001197.RW2
--> Found ISO 250 image: ./P1001198.RW2
--> Found ISO 320 image: ./P1001199.RW2
--> Found ISO 400 image: ./P1001200.RW2
--> Found ISO 500 image: ./P1001201.RW2
--> Found ISO 640 image: ./P1001202.RW2
--> Found ISO 800 image: ./P1001203.RW2
--> Found ISO 1000 image: ./P1001204.RW2
--> Found ISO 1250 image: ./P1001205.RW2
--> Found ISO 1600 image: ./P1001206.RW2
--> Found ISO 2000 image: ./P1001207.RW2
--> Found ISO 2500 image: ./P1001208.RW2
--> Found ISO 3200 image: ./P1001209.RW2
--> Found ISO 4000 image: ./P1001210.RW2
--> Found ISO 5000 image: ./P1001211.RW2
--> Found ISO 6400 image: ./P1001212.RW2
--> Found ISO 8000 image: ./P1001213.RW2
--> Found ISO 10000 image: ./P1001214.RW2
--> Found ISO 12800 image: ./P1001215.RW2
--> Found ISO 16000 image: ./P1001216.RW2
--> Found ISO 20000 image: ./P1001217.RW2
--> Found ISO 25600 image: ./P1001218.RW2

The script will use existing input RAW images for the profiling. No more
shot will be taken.

===> Checking profiling RAW images correctness + Jpeg export
--> ISO 100:
    ./P1001194.RW2
--> ISO 125:
    ./P1001195.RW2
--> ISO 160:
    ./P1001196.RW2
--> ISO 200:
    ./P1001197.RW2
--> ISO 250:
    ./P1001198.RW2
--> ISO 320:
    ./P1001199.RW2
--> ISO 400:
    ./P1001200.RW2
--> ISO 500:
    ./P1001201.RW2
--> ISO 640:
    ./P1001202.RW2
--> ISO 800:
    ./P1001203.RW2
--> ISO 1000:
    ./P1001204.RW2
--> ISO 1250:
    ./P1001205.RW2
--> ISO 1600:
    ./P1001206.RW2
--> ISO 2000:
    ./P1001207.RW2
--> ISO 2500:
    ./P1001208.RW2
--> ISO 3200:
    ./P1001209.RW2
--> ISO 4000:
    ./P1001210.RW2
--> ISO 5000:
    ./P1001211.RW2
--> ISO 6400:
    ./P1001212.RW2
--> ISO 8000:
    ./P1001213.RW2
--> ISO 10000:
    ./P1001214.RW2
--> ISO 12800:
    ./P1001215.RW2
--> ISO 16000:
    ./P1001216.RW2
--> ISO 20000:
    ./P1001217.RW2
--> ISO 25600:
    ./P1001218.RW2

===> Prepare profiling job
--> Remove previous presets
--> Ready to profile images

NOTE: This process takes some time and a lot of memory and disc space
(up-to several gigabytes, depending on the number of ISO settings and
the size of the RAW files.

===> Profile image for "Panasonic - DC-LX100M2 - 100 ISO"
--> Converting ./P1001194.RW2 (ISO 100)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001194.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001194.pfm
--> Fitted parametric curves
--> Flattened ./P1001194.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 125 ISO"
--> Converting ./P1001195.RW2 (ISO 125)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001195.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001195.pfm
--> Fitted parametric curves
--> Flattened ./P1001195.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 160 ISO"
--> Converting ./P1001196.RW2 (ISO 160)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001196.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001196.pfm
--> Fitted parametric curves
--> Flattened ./P1001196.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 200 ISO"
--> Converting ./P1001197.RW2 (ISO 200)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001197.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001197.pfm
--> Fitted parametric curves
--> Flattened ./P1001197.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 250 ISO"
--> Converting ./P1001198.RW2 (ISO 250)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001198.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001198.pfm
--> Fitted parametric curves
--> Flattened ./P1001198.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 320 ISO"
--> Converting ./P1001199.RW2 (ISO 320)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001199.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001199.pfm
--> Fitted parametric curves
--> Flattened ./P1001199.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 400 ISO"
--> Converting ./P1001200.RW2 (ISO 400)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001200.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001200.pfm
--> Fitted parametric curves
--> Flattened ./P1001200.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 500 ISO"
--> Converting ./P1001201.RW2 (ISO 500)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001201.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001201.pfm
--> Fitted parametric curves
--> Flattened ./P1001201.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 640 ISO"
--> Converting ./P1001202.RW2 (ISO 640)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001202.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001202.pfm
--> Fitted parametric curves
--> Flattened ./P1001202.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 800 ISO"
--> Converting ./P1001203.RW2 (ISO 800)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001203.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001203.pfm
--> Fitted parametric curves
--> Flattened ./P1001203.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 1000 ISO"
--> Converting ./P1001204.RW2 (ISO 1000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001204.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001204.pfm
--> Fitted parametric curves
--> Flattened ./P1001204.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 1250 ISO"
--> Converting ./P1001205.RW2 (ISO 1250)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001205.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001205.pfm
--> Fitted parametric curves
--> Flattened ./P1001205.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 1600 ISO"
--> Converting ./P1001206.RW2 (ISO 1600)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001206.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001206.pfm
--> Fitted parametric curves
--> Flattened ./P1001206.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 2000 ISO"
--> Converting ./P1001207.RW2 (ISO 2000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001207.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001207.pfm
--> Fitted parametric curves
--> Flattened ./P1001207.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 2500 ISO"
--> Converting ./P1001208.RW2 (ISO 2500)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001208.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001208.pfm
--> Fitted parametric curves
--> Flattened ./P1001208.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 3200 ISO"
--> Converting ./P1001209.RW2 (ISO 3200)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001209.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001209.pfm
--> Fitted parametric curves
--> Flattened ./P1001209.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 4000 ISO"
--> Converting ./P1001210.RW2 (ISO 4000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001210.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001210.pfm
--> Fitted parametric curves
--> Flattened ./P1001210.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 5000 ISO"
--> Converting ./P1001211.RW2 (ISO 5000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001211.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001211.pfm
--> Fitted parametric curves
--> Flattened ./P1001211.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 6400 ISO"
--> Converting ./P1001212.RW2 (ISO 6400)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001212.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001212.pfm
--> Fitted parametric curves
--> Flattened ./P1001212.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 8000 ISO"
--> Converting ./P1001213.RW2 (ISO 8000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001213.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001213.pfm
--> Fitted parametric curves
--> Flattened ./P1001213.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 10000 ISO"
--> Converting ./P1001214.RW2 (ISO 10000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001214.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001214.pfm
--> Fitted parametric curves
--> Flattened ./P1001214.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 12800 ISO"
--> Converting ./P1001215.RW2 (ISO 12800)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001215.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001215.pfm
--> Fitted parametric curves
--> Flattened ./P1001215.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 16000 ISO"
--> Converting ./P1001216.RW2 (ISO 16000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001216.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001216.pfm
--> Fitted parametric curves
--> Flattened ./P1001216.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 20000 ISO"
--> Converting ./P1001217.RW2 (ISO 20000)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001217.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001217.pfm
--> Fitted parametric curves
--> Flattened ./P1001217.pfm
--> Save generated preset

===> Profile image for "Panasonic - DC-LX100M2 - 25600 ISO"
--> Converting ./P1001218.RW2 (ISO 25600)
RW2 IMAGE
RW2 IMAGE
[export_job] exported to `./P1001218.pfm'
--> Run darktable-noiseprofile
--> Plotting ./P1001218.pfm
--> Fitted parametric curves
--> Flattened ./P1001218.pfm
--> Save generated preset

===> Prepare final pdf
Filelist: ./P1001194.pdf ./P1001194_flat.pdf ./P1001195.pdf ./P1001195_flat.pdf ./P1001196.pdf ./P1001196_flat.pdf ./P1001197.pdf ./P1001197_flat.pdf ./P1001198.pdf ./P1001198_flat.pdf ./P1001199.pdf ./P1001199_flat.pdf ./P1001200.pdf ./P1001200_flat.pdf ./P1001201.pdf ./P1001201_flat.pdf ./P1001202.pdf ./P1001202_flat.pdf ./P1001203.pdf ./P1001203_flat.pdf ./P1001204.pdf ./P1001204_flat.pdf ./P1001205.pdf ./P1001205_flat.pdf ./P1001206.pdf ./P1001206_flat.pdf ./P1001207.pdf ./P1001207_flat.pdf ./P1001208.pdf ./P1001208_flat.pdf ./P1001209.pdf ./P1001209_flat.pdf ./P1001210.pdf ./P1001210_flat.pdf ./P1001211.pdf ./P1001211_flat.pdf ./P1001212.pdf ./P1001212_flat.pdf ./P1001213.pdf ./P1001213_flat.pdf ./P1001214.pdf ./P1001214_flat.pdf ./P1001215.pdf ./P1001215_flat.pdf ./P1001216.pdf ./P1001216_flat.pdf ./P1001217.pdf ./P1001217_flat.pdf ./P1001218.pdf ./P1001218_flat.pdf

===> Prepare final tarball
/run/media/ddyakov/sda9/Pictures/LX100M2_noise_profiles
--> Cleanup

== Noise profiling done! ==

To test the noise profiles locally, run:

  darktable --noiseprofiles ./presets.json

If you're happy with the results, post the following file to us:

  ./darktable-noiseprofile-20190521.tar.gz

If not, probably something went wrong. It's a good idea to get in touch
so we can help you sort it out.
```
