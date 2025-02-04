---
sidebar_position: 4
---

# useStarknetCall

Hook to fetch data from a StarkNet contract. The data is automatically refreshed at every block.

```typescript
import { useStarknetCall } from '@starknet-react/core'

const { data, loading, error, refresh } = useStarknetCall({ contract, method, args })
```

## Parameters

```typescript
{
  contract?: Contract
  method?: string
  args?: T
}
```

## Return Values

```typescript
{
  data?: Array<any>
  loading: boolean
  error?: string
  refresh: () => void
}
```
