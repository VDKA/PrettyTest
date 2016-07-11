# Make Swift Tests results glancable

XCTest uses `stderr` to print results for some reason to you can pipe output using the following.
`swift test 2>&1 | PrettyTest`
`..............x.....................x...............................`

