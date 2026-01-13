# Usage Examples

Below are some sample code snippets showing how to consume our color palette in a React project:

```tsx
import { colors } from '@base/brand-kit';

export const PrimaryButton: React.FC = () => (
  <button style={{ backgroundColor: colors.primary500, color: colors.neutral0 }}>
    Click me
  </button>
);
