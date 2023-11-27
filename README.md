# nvd

This repo contains the regular release of [Fleet](https://fleetdm.com)'s CVE vulnerability database. The database is compiled regulardly from the [National Vulnerability Database](https://nvd.nist.gov/).

### Documentation

To use this repo as a source of NVD CVE data for your Fleet server, set the following environment variable:
```
FLEET_VULNERABILITIES_CVE_FEED_PREFIX_URL=https://github.com/getvictor/nvd-cve/releases/latest/download
```

Complete documentation for Fleet can be found at [https://fleetdm.com/docs](https://fleetdm.com/docs).

### Help

Unsure? If you run into any trouble or questions, click [here](https://fleetdm.com/slack).

### Bugs

If you suspect you've found a bug, please [report the bug here](https://github.com/fleetdm/fleet/issues). Thanks!

### Debug

You can check if downloads are happening with GitHub API. Look for download_count at endpoint like: https://api.github.com/repos/getvictor/nvd-cve/releases

## License

This repo is free and open-source under the MIT License.
