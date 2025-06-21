# Text Loader

- stroke-dasharray: value1 value2
  - Draws a line for value1 length, then draws a gap for value2 length
  - This pattern repeats across the entire text
  - value1 line -> value2 gap -> value1 line -> value2 gap
    stroke-dashoffset: value
- stroke-dashoffset: value
  - Specifies the offset where the pattern starts from value
  - In the code, animating the value creates a rotating effect of the dashArray patterns while they are being filled
