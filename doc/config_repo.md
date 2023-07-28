# Configuracion del repositorio 

There’s only one rule about branches: anything in the master branch is always deployable.

Instead of working in master, changes should be merged in via Pull Requests from other feature branches or from a fork.

To this end, you should protect the master branch to encourage code reviews before changes are merged and deployed. This will prevent work from being performed directly on master, and will foster collaboration among CoA developers.

## Protecting the master branch

- settings
    - code and automation
        - branches

Branch protection rules ---> ```add rule```

Branch name pattern: main
- Protect matching branches
    - require a pull recuest before merging
    - require approvasl
    -  Dismiss stale pull request approvals when new commits are pushed
    -  Require review from Code Owners 

## manage user access to repos

roles

### links a tener en cuenta:

https://docs.github.com/code-security