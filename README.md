# Deprescape
Turn off extensions that use Manifest v2. this exploit is not by me!!!

# Requirements
- chrome://flags
- ExtensionManifestV2Availability policy unset or equal to 0 - it will not work if it is set to 1 or 2.
- - You can find out by going to chrome://policy and searching for the flag. Make sure to check the box that says "Show policies with no value set".
- Extensions that use Manifest v2.
- - You can find out by going to chrome-extension://<extension-id>/manifest.json and searching for the manifest_version (if it is 2, this exploit can work).

# Instructions:
1. Turn the following flags on:
- #extension-manifest-v2-deprecation-warning
- #extension-manifest-v2-deprecation-disabled
- #extension-manifest-v2-deprecation-unsupported (chromeOS v131+)
2. Restart.
3. The extensions that used Manifest v2 should be disabled.

# Credits:
- I'm not too sure but it's in the Titanium Network server (I'm banned from it)
- I know because someone forwarded the original exploit (it's called Deprescape)
