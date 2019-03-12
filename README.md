# gitlab-ci-templates

Templates for projects using GitlabCI

## Release.gitlab-ci.yml

Contains jobs helping with tag creation, release, etc. for projects using GitFlow

Jobs:

- `tag-release-candidate`: manual, only for release branches, create a tag with format `release-<version>-RC-YY-MM-DD_hh-mm`
such as `release-1.2.3-RC-19-02-28_17-59`
- `tag-release`: manual, only for release branches, create a tag with format `release-<version>` such as `release-1.2.3`

## Docker-Tag.gitlab-ci.yml

Contains jobs helping with Docker tag creation, release, etc. for projects using GitFlow

Jobs:

- `tag-docker-rc`: manual, only for release branches, create a tag with format `release-<version>-RC-YY-MM-DD_hh-mm`
such as `release-1.2.3-RC-19-02-28_17-59`
- `tag-docker-release`: manual, only for release branches, create a tag with format `release-<version>` such