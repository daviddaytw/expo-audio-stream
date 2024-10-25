[**@siteed/expo-audio-stream**](../README.md) • **Docs**

***

[@siteed/expo-audio-stream](../README.md) / UseAudioRecorderState

# Interface: UseAudioRecorderState

## Properties

### analysisData?

> `optional` **analysisData**: [`AudioAnalysis`](AudioAnalysis.md)

#### Defined in

[src/ExpoAudioStream.types.ts:91](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L91)

***

### durationMs

> **durationMs**: `number`

#### Defined in

[src/ExpoAudioStream.types.ts:89](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L89)

***

### isPaused

> **isPaused**: `boolean`

#### Defined in

[src/ExpoAudioStream.types.ts:88](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L88)

***

### isRecording

> **isRecording**: `boolean`

#### Defined in

[src/ExpoAudioStream.types.ts:87](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L87)

***

### pauseRecording()

> **pauseRecording**: () => `void`

#### Returns

`void`

#### Defined in

[src/ExpoAudioStream.types.ts:85](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L85)

***

### resumeRecording()

> **resumeRecording**: () => `void`

#### Returns

`void`

#### Defined in

[src/ExpoAudioStream.types.ts:86](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L86)

***

### size

> **size**: `number`

#### Defined in

[src/ExpoAudioStream.types.ts:90](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L90)

***

### startRecording()

> **startRecording**: (`_`) => `Promise`\<[`StartRecordingResult`](StartRecordingResult.md)\>

#### Parameters

• **\_**: [`RecordingConfig`](RecordingConfig.md)

#### Returns

`Promise`\<[`StartRecordingResult`](StartRecordingResult.md)\>

#### Defined in

[src/ExpoAudioStream.types.ts:83](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L83)

***

### stopRecording()

> **stopRecording**: () => `Promise`\<`null` \| [`AudioRecording`](AudioRecording.md)\>

#### Returns

`Promise`\<`null` \| [`AudioRecording`](AudioRecording.md)\>

#### Defined in

[src/ExpoAudioStream.types.ts:84](https://github.com/deeeed/expo-audio-stream/blob/6d10216c587140e4c86296be9540489393fa35a2/packages/expo-audio-stream/src/ExpoAudioStream.types.ts#L84)
