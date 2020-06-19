## Versioning 

Versioning is enabled by default in MyloDocs. When you connect your GitHub repo we look to see if there are any branches that start with `version-`. If none are found we automatically create a branch called `version-1.0` with the most basic files you need. This will get your site up and running. 

Mylodocs will only include GitHub branches that start with `version-`. So for version `1.2` there would be a branch called `version-1.2`.

To select your default branch, append `-main` to the branch name. For example `version-2.0-main`.