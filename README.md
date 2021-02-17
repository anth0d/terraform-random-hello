# terraform-random-hello

This module is an example to be used for simple demonstration.
It has no dependencies to an external service since it uses
the `random` provider.

## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.14 |
| random | >= 3.0.1 |

## Providers

| Name | Version |
|------|---------|
| random | >= 3.0.1 |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| hellos | list of hellos | <pre>object({<br>    hello        = string<br>    second_hello = string<br>  })</pre> | n/a | yes |
| some\_key | this is a some key | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| list\_of\_pets | list of random pet IDs |
| pet | first random pet ID |
| quoted\_some\_key | escaped quoted value of some\_key |

