<file_path>
embed-preview\README.md
</file_path>

<edit_description>
Update README.md for the embed-preview package
</edit_description>

# embed-preview

A React component library for previewing Discord messages with embeds, components, and more. Fully offline and easy to integrate.

## Installation

```bash
npm install embed-preview
```

or

```bash
yarn add embed-preview
```

## Usage

```tsx
import { MessagePreview, Message } from 'embed-preview';

const message: Message = {
  content: 'Hello, world!',
  embeds: [
    {
      title: 'Example Embed',
      description: 'This is an example embed.',
      color: 0x00ff00,
    },
  ],
  components: [],
};

function App() {
  return <MessagePreview msg={message} />;
}
```

## Props

- `msg`: A `Message` object containing the message data.

## Features

- Preview Discord messages with text, embeds, and interactive components.
- Supports buttons, select menus, and more.
- Fully offline - no API calls required.
- TypeScript support with full type definitions.

## License

MIT