## 3.7.6

- :bug: `bundle.request.data` should always be an object in `pre_oauthv2_refresh` ([#294](https://github.com/zapier/zapier-platform/pull/294))

## 3.7.5

- :bug: Make response headers case-insensitive ([#253](https://github.com/zapier/zapier-platform/pull/253))
- :bug: `bundle.request.data` should be undefined in `pre_custom_action_fields` ([#256](https://github.com/zapier/zapier-platform/pull/256))

## 3.7.4

- :bug: Fix env vars in curlies not resolving properly ([#237](https://github.com/zapier/zapier-platform/pull/237))

## 3.7.3

- :bug: Encode URL before sending a request ([#235](https://github.com/zapier/zapier-platform/pull/235))
- :hammer: Refactor tests to use Zapier-hosted httpbin ([#228](https://github.com/zapier/zapier-platform/pull/228))
- :hammer: Fix tests where inline function source isn't compiled ([#226](https://github.com/zapier/zapier-platform/pull/226))

## 3.7.2

- :bug: Prune body if `allowGetBody` and body is empty ([#224](https://github.com/zapier/zapier-platform/pull/224))

## 3.7.1

- :bug: Allow `post_read_resource` to return an array ([#219](https://github.com/zapier/zapier-platform/pull/219))
- :hammer: Upgrade dependencies ([#218](https://github.com/zapier/zapier-platform/pull/218))

## 3.7.0

- :tada: More complete bundle logs ([#213](https://github.com/zapier/zapier-platform/pull/213))
- :bug: Trim bloated bundles for `KEY_post` methods ([#213](https://github.com/zapier/zapier-platform/pull/213))

## 3.6.0

- :nail_care: Allow GET requests to have body (requires zapier-platform-core 9.4.0+) ([#195](https://github.com/zapier/zapier-platform/pull/195))
- :bug: More "reliably interpolate arrays or objects to a string" ([#203](https://github.com/zapier/zapier-platform/pull/203))
- :hammer: Upgrade `request` package ([#196](https://github.com/zapier/zapier-platform/pull/196))

## 3.5.0

- :tada: Add support for unbounded curlies ([#194](https://github.com/zapier/zapier-platform/pull/194))

## 3.4.0

- :tada: Allow to "reliably interpolate arrays or objects to a string" ([#190](https://github.com/zapier/zapier-platform/pull/190))

## 3.3.3

- :bug: Run post method first before throwing error for response status ([#183](https://github.com/zapier/zapier-platform/pull/183))

## 3.3.2

- :bug: Fix missing `console.log` ([#182](https://github.com/zapier/zapier-platform/pull/182))

## 3.3.1

- :bug: Add full jQuery support ([#181](https://github.com/zapier/zapier-platform/pull/181))

## 3.3.0

- :tada: Log converted bundles ([#177](https://github.com/zapier/zapier-platform/pull/177))
