> Generic Page Structure Sample

```typescript
import type { NextPage } from "next";
import Main from "../layouts/Main";

const Page: NextPage = () => {
  return (
    <Main pageTitle="Page Title">
      <h1>{PAGE_CONTENT}</h1>
    </Main>
  );
};

export default Page;
```

> Generic Component Structure Sample

```typescript
import React from "react";
import Flex from "@chakra-ui/react";

const Component: React.FC<{ props: PropTypes }> = ({ props }) => {
  return (
    <Flex as="section">
      <Text>PAGE_CONTENT</Text>
    </Flex>
  );
};

export default Component;
```
