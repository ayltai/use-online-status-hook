# React Hook: use-online-status
A React hook to observe online status.

[![CircleCI](https://img.shields.io/circleci/project/github/ayltai/use-online-status-hook/master.svg?style=flat)](https://circleci.com/gh/ayltai/use-online-status-hook) ![Maintenance](https://img.shields.io/maintenance/yes/2020) [![Release](https://img.shields.io/github/release/ayltai/use-online-status-hook.svg?style=flat)](https://github.com/ayltai/use-online-status-hook/releases) [![License](https://img.shields.io/github/license/ayltai/use-online-status-hook.svg?style=flat)](https://github.com/ayltai/use-online-status-hook/blob/master/LICENSE)

[![Buy me a coffee](https://img.shields.io/static/v1?label=Buy%20me%20a&message=coffee&color=important&style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://buymeacoff.ee/ayltai)

## Installation
```shell script
npm install @ayltai/use-online-status
```

## Usage
```jsx
import { useOnlineStatus, } from '@ayltai/use-online-status';

const Example = () => {
    const isOnline = useOnlineStatus();

    return (
        <>
            {`You are ${isOnline ? 'online' : 'offline'}`}
        </>
    );
};
```
