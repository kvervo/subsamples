# Subtitle Format Test Samples
Diverse synthetic subtitle files for testing purposes
Expected formats:
* SRT
* STL
* Teletext

## STL

Officially known as EBU 3264. Also known as EBU Subtitles or EBU Teletext.

The EBU Subtitling Data Exchange Format (EBU-STL) is a legacy, out-of-band caption file format used primarily in Europe for authoring and interchange.

Official usage data is unavailable, but most caption authoring tools support EBU-STL. EBU-STL files typically have the extension ".STL." The format describes captions using a fixed character set. The format stores a sequence of Text and Timing Information (TTI) blocks. Each TTI block specifies a row of characters, an associated time code, and other metadata. The character codes used for the captions may optionally match the Teletext codes.

### References
* [EBU-3264](https://tech.ebu.ch/docs/tech/tech3264.pdf) is the specification of EBU-STL.
* [EBU-3360](https://tech.ebu.ch/docs/tech/tech3360.pdf) provides information about strategies that may be used to convert EBU-STL to EBU-TT

### Test File
Sample file contains the following characteristics in order or appearance:
1. Special Characters based on Code Table 00 - Latin alphabet
2. Italic formatting
3. Underline formatting
4. Single breakline
5. Double breaklines
6. Multiple breaklines
7. Test that 0Ah is not converted to breakline
8. STL extension test (2 TTI blocks)
9. STL extension test (3 TTI blocks)