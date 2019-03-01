Simple browser/node module to generate a dummy, silent mp3 file of a specific duration.

## Installation
    $ npm install mp3-dummy

## Usage
    const mp3Dummy = require('mp3-dummy');

	// Generates a 10 second mp3 file
	const mp3File = mp3Dummy(10)

## API
    mp3Dummy(duration: number): ArrayBuffer