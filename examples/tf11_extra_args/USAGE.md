### Requirements

The following requirements are needed by this module:

- aws (< 2.2.0)

- consul (>= 1.0.0)

### Providers

The following providers are used by this module:

- aws (< 2.2.0)

- consul (>= 1.0.0)

### Inputs

The following input variables are supported:

#### extra\_environment

Description: List of additional environment variables

Type: `list`

Default: `[]`

#### extra\_tags

Description: Additional tags

Type: `map`

Default: `{}`

#### instance\_count

Description: Number of instances to create

Type: `string`

Default: `"1"`

#### instance\_name

Description: Instance name prefix

Type: `string`

Default: `"test-"`

#### subnet\_ids

Description: A list of subnet ids to use

Type: `list`

Default: n/a

#### vpc\_id

Description: The id of the vpc

Type: `string`

Default: n/a

### Outputs

The following outputs are exported:

#### vpc\_id

Description: The Id of the VPC
