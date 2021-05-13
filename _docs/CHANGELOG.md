# CHANGELOG

- Update pgk `github.com/swaggo/swag` to `v1.6.7` to fix bug `checksum mismatch` when run `go install -v ./...` in `Dockerfile.dev`
  - Issue: https://github.com/swaggo/swag/issues/712 
- Add `Dockerfile.dev` and `docker-compose.dev.yml` for build development
  - Fixed version image golang, node, ubuntu