<p align="center" style="color: #343a40">
  <img
    src="https://s3.amazonaws.com/pix.iemoji.com/images/emoji/apple/ios-12/256/woman-cook.png" 
    alt="react-recipes-logo" 
    height="150" 
    width="150"
    >
  <h1 align="center">React Recipes</h1>
</p>
<p align="center" style="font-size: 1.2rem;">A React Hooks utility library containing popular customized hooks</p>
<p align="center" style="font-size: 1.2rem;">What's your favorite dish?</p>

[![Build Status](https://travis-ci.com/craig1123/react-recipes.svg?branch=master)](https://travis-ci.com/craig1123/react-recipes)
![](https://badgen.net/npm/v/react-recipes)
![](https://badgen.net/bundlephobia/minzip/react-recipes)
![](https://badgen.net/npm/dt/react-recipes)
![](https://img.shields.io/badge/license-MIT-green.svg)

```bash
npm i react-recipes --save
```

```bash
yarn add react-recipes
```

## 🥘 Recipes Documentation

| Name                                                                | Returns                                               | Arguments                                                                               |
| ------------------------------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------------------------------------------- |
| 🍪 [`useCookie`](./docs/useCookie.md)                               | [cookieValue, updateCookie, deleteCookie]             | (cookieName, initialValue)                                                              |
| 🥠 [`useCopyClipboard`](./docs/useCopyClipboard.md)                 | [isCopied, setIsCopied]                               | (duration: 2000)                                                                        |
| 🍩 [`useDarkMode`](./docs/useDarkMode.md)                           | [enabled, setEnabledState]                            | -                                                                                       |
| 🍜 [`useDebounce`](./docs/useDebounce.md)                           | debouncedValue                                        | (value, delay)                                                                          |
| 🥡 [`useDimensions`](./docs/useDimensions.md)                       | [ref, dimensions, node]                               | (liveMeasure: true, delay: 250, initialDimensions: {}, effectDependencies: [])          |
| 🍳 [`useEventListener`](./docs/useEventListener.md)                 | -                                                     | (eventName, handle, element: window)                                                    |
| 🌯 [`useGeolocation`](./docs/useGeolocation.md)                     | { latitude, longitude, timestamp, accuracy, error }   | (watch: false, settings: {enableHighAccuracy: false, timeout: Infinity, maximumAge: 0}) |
| 🌭 [`useHover`](./docs/useHover.md)                                 | [callbackRef, value]                                  | -                                                                                       |
| 🍦 [`useInterval`](./docs/useInterval.md)                           | [delay, ...effectDependencies]                        | (callback, delay, runOnLoad: false, effectDependencies: [])                             |
| 🍐 [`useIsClient`](./docs/useIsClient.md)                           | isClient                                              | -                                                                                       |
| 🥧 [`useKeyPress`](./docs/useKeyPress.md)                           | keyPressed                                            | (targetKey)                                                                             |
| 🍱 [`useLocalStorage`](./docs/useLocalStorage.md)                   | [storedValue, setValue]                               | (key, initialValue)                                                                     |
| 🍋 [`useLockBodyScroll`](./docs/useLockBodyScroll.md)               | -                                                     | -                                                                                       |
| 🍉 [`useMedia`](./docs/useMedia.md)                                 | value                                                 | (queries, values, defaultValue)                                                         |
| 🥭 [`useMultiKeyPress`](./docs/useMultiKeyPress.md)                 | keysPressed                                           | (targetKey)                                                                             | 
| 🥑 [`useOnClickOutside`](./docs/useOnClickOutside.md)               | -                                                     | (ref, callback)                                                                         | 
| 🥒 [`useOnlineStatus`](./docs/useOnlineStatus.md)                   | onlineStatus                                          | -                                                                                       | 
| 🍿 [`usePrevious`](./docs/usePrevious.md)                           | previous                                              | (value)                                                                                 |
| 🍣 [`useScript`](./docs/useScript.md)                               | [loaded, error]                                       | (src)                                                                                   |
| 🍖 [`useSpeechRecognition`](./docs/useSpeechRecognition.md)         | { supported, listen, listening, stop }                | ({ onEnd })                                                                             |
| 🍗 [`useSpeechSynthesis`](./docs/useSpeechSynthesis.md)             | { supported, speak, speaking, cancel, voices }        | ({ onEnd, onResult })                                                                   |
| 🍏 [`useThrottle`](./docs/useThrottle.md)                           | throttledValue                                        | (value, ms: 250)                                                                        |
| 🍷 [`useWhyDidYouUpdate`](./docs/useWhyDidYouUpdate.md)             | -                                                     | (name, props)                                                                           |
| 🥖 [`useWindowScroll`](./docs/useWindowScroll.md)                   | { x, y }                                              | -                                                                                       |
| 🥮 [`useWindowSize`](./docs/useWindowSize.md)                       | { height, width }                                     | (initialWidth, initialHeight)                                                           |
| 🥝 [`useWorker`](./docs/useWorker.md)                               | worker instance                                       | (scriptPath, workerOptions, attributes)                                                 |
