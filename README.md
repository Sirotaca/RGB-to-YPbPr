# RGB to YPbPr Converter
This board accepts RGBHV or RGBS with any sync polarity via a DE-15 (VGA) input and converts it into YPbPr component video. Video timing is unchanged, so ensure that your display or video processor is compatible with the resolution of the source. The transformation matrix uses Rec. 601 coefficients, so resolutions higher than 480p will have slightly incorrect colors.
