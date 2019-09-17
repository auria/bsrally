Install from Snap Store:

<a href="https://snapcraft.io/bsrally">
  <img alt="bsrally" src="https://snapcraft.io/bsrally/badge.svg" />
</a>

# bsrally

```
How to run tests:
1. Source ~/openrc
2. bsrally.rallyinit
3. bsrally.tempestinit
4. bsrally.rally verify start --load-list testlist.txt

Make sure to fix the tempest.conf with image ID's, network ID's etc to pass all tests.

# Run a sample tempest test
bsrally.rally verify start --id b50b0563-cec1-4a4f-8e3b-0e501f7b9669 --pattern tempest.api.compute.images.test_images_oneserver.ImagesOneServerTestJSON.test_create_delete_image
```
