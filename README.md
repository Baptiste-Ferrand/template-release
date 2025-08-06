# template-release
Juste a repository for a template of an workflow who : 
  - manage versioning (major, minor, micro)
  - depend on the branche create tag (pre-prod if is in develop)
  - create a tag whit the version and tag if is in pre-prod (develop branche) (tag loock like 1.0.0-pre-prod or 1.0.0 if in prod and if is a last version using tag latest)
  - update the changelog whit new feature or fix in
  - create release assosiated whit the tag created before, using the changelog for showing new change
  - build and publish package whit the actual tag if develop (1.0.0-pre-prod) if in main and the newest (1.0.0, latest) 
    
