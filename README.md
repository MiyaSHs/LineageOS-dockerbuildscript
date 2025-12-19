#### **DESCRIPTION**
WIP (but working!!!) script to automate docker building lineageos, with options whether to build base or with microg, and extra (currently trying root selection and applying, and later gonna try kernel optimizing, maybe even easy way to add system apps)

> ##### *INFO*
> unless the docker script it relies on (https://github.com/lineageos4microg/docker-lineage-cicd) or microg or one of the root options it lists gets archived or changes way of applying/function, this script should keep working for newer android versions, devices (supported by lineageos officially, unnofficial devices would require a custom manifest pointing to their repos, kernel, device config, etc. Adding of a custom manifest is going to take time to script, so if i havent implemented a "custom" device option, check the docker image wiki), and root versions, as it just fetches the latest version of each on eachrun and builds.
