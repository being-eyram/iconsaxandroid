# Iconsax-android
An unofficial vuesax icons[(iconsax)](https://iconsax.io) library for android. Full list of icons can be found [here](https://iconsax-react.pages.dev/).   
Iconsax-android icons come in 6 distinct styles—1000 icons per style:  

- Linear
- Outline
- Bold
- Bulk 
- Broken 
- TwoTone 

## Download
[![Maven Central](https://img.shields.io/maven-central/v/io.github.being-eyram/iconsax-android?color=G&style=for-the-badge)](https://search.maven.org/artifact/io.github.being-eyram/iconsax-android)

### Gradle

Add the dependency below to your **module**'s `build.gradle` file:
```gradle
dependencies {
    implementation "io.github.being-eyram:iconsax-android:1.0.0"
}
```

## Usage
`Iconsax.StyleName.IconName`

For example, you can use the iconsax-android in a Jetpack Compose project as seen below:

```kotlin
  Icon(
        painter = painterResource(IconSax.TwoTone.ArchiveSlash),
        contentDescription = null, 
        tint = Color.Red
    )
```

## License

```
Distributed under the MIT License

Copyright (c) 2023 Eyram Michael

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
