# setup-vulkan-sdk v1.3.0

This is a GitHub action to build and install the Vulkan SDK.

Forked from [humbletim/install-vulkan-sdk](https://github.com/humbletim/install-vulkan-sdk) so we can keep it current.

### Example

```yaml
  -name: Prepare Vulkan SDK
   uses: pelicanmapping/setup-vulkan-sdk@v1.3.0
   with:
     vulkan-query-version: 1.3.204.0
     vulkan-components: Vulkan-Headers, Vulkan-Loader
     vulkan-use-cache: true
```

### References
- [Vulkan SDK](https://www.lunarg.com/vulkan-sdk/)
- [Vulkan SDK web services API](https://vulkan.lunarg.com/content/view/latest-sdk-version-api)
- [humbletim/install-vulkan-sdk](https://github.com/humbletim/install-vulkan-sdk)
