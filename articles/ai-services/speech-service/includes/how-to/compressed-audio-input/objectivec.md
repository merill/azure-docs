---
author: eric-urban
ms.service: cognitive-services
ms.topic: include
ms.date: 9/22/2020
ms.author: eur
---

[!INCLUDE [Header](../../common/objectivec.md)]

The Speech SDK for Objective-C does not support compressed audio.

The default audio streaming format is WAV (16 kHz or 8 kHz, 16-bit, and mono PCM). To input a compressed audio file (e.g. mp3), you must first convert it to a WAV file in the default input format. To stream compressed audio, you must first decode the audio buffers to the default input format. For more information, see [How to use the audio input stream](../../../how-to-use-audio-input-streams.md).
