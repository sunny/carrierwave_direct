This is a fork of [CarrierWaveDirect](https://github.com/dwilkie/carrierwave_direct) with the following patches applied:

- [#96](https://github.com/dwilkie/carrierwave_direct/pull/96)
  Convert time format in policy to string using iso8601 in policy
- [#103](https://github.com/dwilkie/carrierwave_direct/pull/103)
  Stack level too deep when mount on a collumn named "file"
- [#155](https://github.com/dwilkie/carrierwave_direct/pull/155)
  Let Carrierwave generate urls. Fixes
  [#123](https://github.com/dwilkie/carrierwave_direct/issues/123)
  [#151](https://github.com/dwilkie/carrierwave_direct/issues/151)
- [#192](https://github.com/dwilkie/carrierwave_direct/pull/192)
  Update policies & signature sto use Aws sig v4 (AWS4-HMAC-SHA256). Fixes
  [#183](https://github.com/dwilkie/carrierwave_direct/issues/183)
