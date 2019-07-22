## Docker Engine

Type that represents a Docker runtime to run multiple Docker container applications on a single host.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `DockerRuntime` | `radon.nodes.docker.DockerRuntime` | 1.0.0 | `tosca.nodes.Container.Runtime` |

In the following, the properties, attributes, capabilities, and requirements changed from / added to the parent type are listed:

### Properties

| Name | Required | Type | Constraint | Default Value | Description |
|:---- |:-------- |:---- |:---------- |:------------- |:----------- |  
| `port` | `true` | `integer` | N/A | 2375 | Exposed port of the Docker daemon |

### Capabilities

| Name | Type | Valid Source Types | Occurrences |
|:---- |:---- |:------------------ |:----------- |
| `docker` | `radon.capabilities.container.DockerRuntime` | `radon.nodes.docker.DockerApplication` | [1, UNBOUNDED] |

---