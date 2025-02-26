# unb
unb

# Requirements
- chrome://flags
- ExtensionManifestV2Availability policy unset or equal to 0 (won't work if it is 1 or 2)
- - You can find out by going to chrome://policy and searching for the flag. Make sure to enable "Show policies with no value set".

# Instructions:
1. Turn the following flags on:
- #extension-manifest-v2-deprecation-warning
- #extension-manifest-v2-deprecation-disabled
- #extension-manifest-v2-deprecation-unsupported
2. Restart.
3. The extensions that used Manifest v2 should be disabled.

Credits:
I'm not too sure but it's in the Titanium Network server (I'm banned from it)
I know because someone forwarded the original exploit
