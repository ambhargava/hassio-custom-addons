Hass.io add-on experiments
--------------------------

These are some random experiments for Hass.io add-ons.

## How to add repository to Hass.io

[Follow repository installation instructions](https://home-assistant.io/hassio/installing_third_party_addons/) with the url `https://github.com/ambhargava/hassio-custom-addons`.

## Additions in this fork
Original work by: [greylurk](https://github.com/greylurk/hassio-custom-addons)
Updates by: [rafa400](https://github.com/rafa400/hassio-custom-addons)

My fork here just fixes the error "s6-overlay-suexec: fatal: can only run as pid 1" that I was getting when starting the OpenVPN addon in Home Assistant. Based on [this suggestion](https://community.home-assistant.io/t/s6-overlay-suexec-fatal-can-only-run-as-pid-1-error-when-starting-ring-livestream/448456/14), I added a configuration "init:false" in the docker config file. 
