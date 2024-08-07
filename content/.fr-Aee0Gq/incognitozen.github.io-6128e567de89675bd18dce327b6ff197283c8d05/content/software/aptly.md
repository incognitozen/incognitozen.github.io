---
title: aptly
draft: false 
website: https://www.aptly.info
classification: ['Repository Management Softwares']
platform: ['Web']
keywords: ['atlassian_bitbucket_server', 'bazaar', 'beanstalk', 'circleci', 'gemfury', 'gitbook', 'helix_core', 'jfrog_mission_control', 'mirage', 'optimizely', 'packagist', 'packagr', 'pulp', 'release_lifecycle_management', 'rhodecode', 'sourceanywhere', 'springloops', 'fpm', 'mrepo']
image: 2020/04/aptly.png
---
Aptly is a swiss army knife for Debian repository management: it allows you to mirror remote repositories, manage local package repositories, take snapshots, pull new versions of packages along with dependencies, publish as Debian repository. Aptly is available both as CLI tool and HTTP REST service.

<strong>Mirror repository</strong>: Take and update mirrors of any Debian/Ubuntu remote repository.

<strong>Publish your packages: </strong>Manage your own repositories of packages, merge them with offical and publish the result.

<strong>Take snapshot: </strong>At any point in time, take snapshot of the mirror to fix current set of packages.

<strong>Publish snapshot: </strong>Any snapshot could be published back as repository (only HTTP server is required).

<strong>Merge snapshots: </strong>Merge two or more snapshots into one snapshot: e.g. merge wheezy and wheezy-updates.

<strong>Upgrade package versions: </strong>New package version available in backports? Pull only single package with dependencies from backports into snapshot of stable repository.

<strong>Filter repository: </strong>Don't download packages that are not required, controlling dependencies between them.

<strong>Publishing to S3: </strong>Publish your repositories directly to Amazon S3 as public or private repositories.

<strong>Package search: </strong>Search for specific packages, their inclusion into snapshots, etc.

<strong>REST API: </strong>Upload packages using HTTP, manage your repositories, snapshots, published repositories etc.