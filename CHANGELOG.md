# Changelog

## [1.0.6] - 2023-06-15

### Documentation

- Add build-locale-archive to the ignore list

### Features

- Check for _cgo_init (fixes 4.10)

## [1.0.5] - 2023-06-15

### Features

- Ignore CGO_ENABLED for golang <= 1.17 (fixes 4.10)

### Build

- Add latest to changelog generation

## [1.0.4] - 2023-06-15

### Documentation

- Add release information blurb

### Miscellaneous Tasks

- Use upstream golang image and remove port

### Performance

- Disable cgo... allows for slightly smaller binary

## [1.0.3] - 2023-06-14

### Miscellaneous Tasks

- first gitlab pipeline release

## [1.0.2] - 2023-06-14

### Miscellaneous Tasks

- Use git describe for version info
- Artifact build only on tags
- Update .gitlab-ci.yml file
- Use git describe for version info

## [1.0.1] - 2023-06-14

### Features

- Skip CGO_ENABLED check on go versions < 1.17
- Ignore tini-static
- Add golang tags validation
