|     | model_name           |   mean |   median |   number_per_run | memory                           | do_compile   |   batch_size | is_fp16   |   image_size | cudnn_benchmark   |
|----:|:---------------------|-------:|---------:|-----------------:|:---------------------------------|:-------------|-------------:|:----------|-------------:|:------------------|
|   0 | resnet34             |   3.86 |     3.88 |              100 | Memory used: 57.642578125 MB     | False        |            1 | True      |          224 | False             |
|   2 | resnet34             |   3.78 |     3.8  |              100 | Memory used: 83.79443359375 MB   | False        |            1 | True      |          640 | False             |
|   4 | resnet34             |   3.58 |     3.56 |              100 | Memory used: 66.89501953125 MB   | False        |            4 | True      |          224 | False             |
|   6 | resnet34             |   8.2  |     8.19 |               10 | Memory used: 173.91943359375 MB  | False        |            4 | True      |          640 | False             |
|   8 | resnet34             |   3.82 |     3.83 |              100 | Memory used: 82.20751953125 MB   | False        |            8 | True      |          224 | False             |
|  10 | resnet34             |  14.63 |    14.64 |               10 | Memory used: 296.39501953125 MB  | False        |            8 | True      |          640 | False             |
|  12 | resnet34             |   4.38 |     4.38 |              100 | Memory used: 112.02001953125 MB  | False        |           16 | True      |          224 | False             |
|  14 | resnet34             |  27.39 |    27.39 |               10 | Memory used: 540.41943359375 MB  | False        |           16 | True      |          640 | False             |
|  16 | resnet34             |   7.78 |     7.79 |              100 | Memory used: 173.39501953125 MB  | False        |           32 | True      |          224 | False             |
|  18 | resnet34             |  53.66 |    53.68 |               10 | Memory used: 1028.41943359375 MB | False        |           32 | True      |          640 | False             |
|  20 | resnet34             |  14.63 |    14.6  |               10 | Memory used: 290.91943359375 MB  | False        |           64 | True      |          224 | False             |
|  22 | resnet34             | 106.13 |   106.19 |               10 | Memory used: 2002.41943359375 MB | False        |           64 | True      |          640 | False             |
|  24 | resnext50_32x4d      |   5.3  |     5.17 |              100 | Memory used: 188.126953125 MB    | False        |            1 | True      |          224 | False             |
|  26 | resnext50_32x4d      |   5.54 |     5.44 |              100 | Memory used: 211.65234375 MB     | False        |            1 | True      |          640 | False             |
|  28 | resnext50_32x4d      |   5.13 |     4.99 |              100 | Memory used: 200.90234375 MB     | False        |            4 | True      |          224 | False             |
|  30 | resnext50_32x4d      |  15.31 |    15.27 |               10 | Memory used: 306.08984375 MB     | False        |            4 | True      |          640 | False             |
|  32 | resnext50_32x4d      |   5.44 |     5.49 |              100 | Memory used: 214.98046875 MB     | False        |            8 | True      |          224 | False             |
|  34 | resnext50_32x4d      |  29.21 |    29.21 |               10 | Memory used: 478.05859375 MB     | False        |            8 | True      |          640 | False             |
|  36 | resnext50_32x4d      |   8.56 |     8.54 |               10 | Memory used: 256.18359375 MB     | False        |           16 | True      |          224 | False             |
|  38 | resnext50_32x4d      |  56.47 |    56.46 |               10 | Memory used: 794.30908203125 MB  | False        |           16 | True      |          640 | False             |
|  40 | resnext50_32x4d      |  15.77 |    15.67 |               10 | Memory used: 329.90234375 MB     | False        |           32 | True      |          224 | False             |
|  42 | resnext50_32x4d      | 106.6  |   106.44 |                1 | Memory used: 1532.30908203125 MB | False        |           32 | True      |          640 | False             |
|  44 | resnext50_32x4d      |  29.56 |    29.54 |               10 | Memory used: 472.18359375 MB     | False        |           64 | True      |          224 | False             |
|  46 | resnext50_32x4d      | 215.93 |   215.79 |                1 | Memory used: 3006.30908203125 MB | False        |           64 | True      |          640 | False             |
|  48 | clip_vision_vit-b/32 |   5.63 |     5.53 |              100 | Memory used: 186.30322265625 MB  | False        |            1 | True      |          224 | False             |
|  50 | clip_vision_vit-b/32 |   6.27 |     6.25 |              100 | Memory used: 189.30810546875 MB  | False        |            4 | True      |          224 | False             |
|  52 | clip_vision_vit-b/32 |   6.62 |     6.76 |              100 | Memory used: 194.3662109375 MB   | False        |            8 | True      |          224 | False             |
|  54 | clip_vision_vit-b/32 |   6.68 |     6.68 |              100 | Memory used: 205.9912109375 MB   | False        |           16 | True      |          224 | False             |
|  56 | clip_vision_vit-b/32 |   9.21 |     9.2  |               10 | Memory used: 229.4912109375 MB   | False        |           32 | True      |          224 | False             |
|  58 | clip_vision_vit-b/32 |  17.05 |    17.04 |               10 | Memory used: 274.4599609375 MB   | False        |           64 | True      |          224 | False             |
|  60 | clip_vision_vit-l/14 |  10.67 |    10.33 |               10 | Memory used: 597.763671875 MB    | False        |            1 | True      |          224 | False             |
|  62 | clip_vision_vit-l/14 |  19.47 |    19.5  |               10 | Memory used: 623.06640625 MB     | False        |            4 | True      |          224 | False             |
|  64 | clip_vision_vit-l/14 |  36.85 |    36.86 |               10 | Memory used: 655.9921875 MB      | False        |            8 | True      |          224 | False             |
|  66 | clip_vision_vit-l/14 |  66.8  |    66.78 |               10 | Memory used: 722.5390625 MB      | False        |           16 | True      |          224 | False             |
|  68 | clip_vision_vit-l/14 | 131.06 |   130.96 |                1 | Memory used: 855.6328125 MB      | False        |           32 | True      |          224 | False             |
|  70 | clip_vision_vit-l/14 | 248.01 |   248.23 |                1 | Memory used: 1121.8203125 MB     | False        |           64 | True      |          224 | False             |
|  72 | clip_vision_vit-rn50 |   5.9  |     5.86 |              100 | Memory used: 213.09912109375 MB  | False        |            1 | True      |          224 | False             |
|  74 | clip_vision_vit-rn50 |   5.69 |     5.55 |              100 | Memory used: 225.06201171875 MB  | False        |            4 | True      |          224 | False             |
|  76 | clip_vision_vit-rn50 |   5.86 |     5.95 |              100 | Memory used: 243.04638671875 MB  | False        |            8 | True      |          224 | False             |
|  78 | clip_vision_vit-rn50 |   8.46 |     8.45 |               10 | Memory used: 270.23388671875 MB  | False        |           16 | True      |          224 | False             |
|  80 | clip_vision_vit-rn50 |  15.48 |    15.48 |               10 | Memory used: 342.79638671875 MB  | False        |           32 | True      |          224 | False             |
|  82 | clip_vision_vit-rn50 |  29.37 |    29.39 |               10 | Memory used: 448.98388671875 MB  | False        |           64 | True      |          224 | False             |
|  84 | resnet34             |   3.8  |     3.82 |              100 | Memory used: 57.642578125 MB     | False        |            1 | True      |          224 | True              |
|  85 | resnet34             |   3.72 |     3.78 |              100 | Memory used: 66.89501953125 MB   | False        |            4 | True      |          224 | True              |
|  86 | resnet34             |   3.72 |     3.76 |              100 | Memory used: 82.20751953125 MB   | False        |            8 | True      |          224 | True              |
|  87 | resnet34             |   4.26 |     4.26 |              100 | Memory used: 112.02001953125 MB  | False        |           16 | True      |          224 | True              |
|  88 | resnet34             |   7.56 |     7.56 |               10 | Memory used: 173.64501953125 MB  | False        |           32 | True      |          224 | True              |
|  89 | resnet34             |  14.18 |    14.18 |               10 | Memory used: 290.89501953125 MB  | False        |           64 | True      |          224 | True              |
|  90 | resnext50_32x4d      |   5.39 |     5.43 |              100 | Memory used: 188.509765625 MB    | False        |            1 | True      |          224 | True              |
|  91 | resnext50_32x4d      |   5.3  |     5.32 |              100 | Memory used: 203.15234375 MB     | False        |            4 | True      |          224 | True              |
|  92 | resnext50_32x4d      |   5.34 |     5.36 |              100 | Memory used: 220.98046875 MB     | False        |            8 | True      |          224 | True              |
|  93 | resnext50_32x4d      |   8.29 |     8.29 |               10 | Memory used: 146.59423828125 MB  | False        |           16 | True      |          224 | True              |
|  94 | resnext50_32x4d      |  15.54 |    15.54 |               10 | Memory used: 292.40234375 MB     | False        |           32 | True      |          224 | True              |
|  95 | resnext50_32x4d      |  29.27 |    29.29 |               10 | Memory used: 418.68359375 MB     | False        |           64 | True      |          224 | True              |
|  96 | clip_vision_vit-b/32 |   6.18 |     6.2  |              100 | Memory used: 183.03125 MB        | False        |            1 | True      |          224 | True              |
|  97 | clip_vision_vit-b/32 |   6.31 |     6.2  |              100 | Memory used: 188.5537109375 MB   | False        |            4 | True      |          224 | True              |
|  98 | clip_vision_vit-b/32 |   6.66 |     6.73 |              100 | Memory used: 194.3662109375 MB   | False        |            8 | True      |          224 | True              |
|  99 | clip_vision_vit-b/32 |   6.49 |     6.3  |              100 | Memory used: 205.9912109375 MB   | False        |           16 | True      |          224 | True              |
| 100 | clip_vision_vit-b/32 |   9.18 |     9.2  |               10 | Memory used: 229.4912109375 MB   | False        |           32 | True      |          224 | True              |
| 101 | clip_vision_vit-b/32 |  16.94 |    16.96 |               10 | Memory used: 274.4599609375 MB   | False        |           64 | True      |          224 | True              |
| 102 | clip_vision_vit-l/14 |  10.78 |    11.13 |               10 | Memory used: 597.763671875 MB    | False        |            1 | True      |          224 | True              |
| 103 | clip_vision_vit-l/14 |  19.34 |    19.33 |               10 | Memory used: 623.06640625 MB     | False        |            4 | True      |          224 | True              |
| 104 | clip_vision_vit-l/14 |  36.52 |    36.61 |               10 | Memory used: 655.9921875 MB      | False        |            8 | True      |          224 | True              |
| 105 | clip_vision_vit-l/14 |  66.67 |    66.73 |               10 | Memory used: 722.5390625 MB      | False        |           16 | True      |          224 | True              |
| 106 | clip_vision_vit-l/14 | 131.02 |   131.14 |                1 | Memory used: 855.6328125 MB      | False        |           32 | True      |          224 | True              |
| 107 | clip_vision_vit-l/14 | 247.84 |   247.74 |                1 | Memory used: 1121.8203125 MB     | False        |           64 | True      |          224 | True              |
| 108 | clip_vision_vit-rn50 |   5.99 |     6.11 |              100 | Memory used: 215.03662109375 MB  | False        |            1 | True      |          224 | True              |
| 109 | clip_vision_vit-rn50 |   5.9  |     5.94 |              100 | Memory used: 221.23388671875 MB  | False        |            4 | True      |          224 | True              |
| 110 | clip_vision_vit-rn50 |   5.94 |     6.03 |              100 | Memory used: 238.45263671875 MB  | False        |            8 | True      |          224 | True              |
| 111 | clip_vision_vit-rn50 |   8.31 |     8.32 |               10 | Memory used: 276.35888671875 MB  | False        |           16 | True      |          224 | True              |
| 112 | clip_vision_vit-rn50 |  15.28 |    15.29 |               10 | Memory used: 293.79638671875 MB  | False        |           32 | True      |          224 | True              |
| 113 | clip_vision_vit-rn50 |  28.83 |    28.83 |               10 | Memory used: 473.48388671875 MB  | False        |           64 | True      |          224 | True              |
| 114 | resnet34             |   3.69 |     3.72 |              100 | Memory used: 83.77001953125 MB   | False        |            1 | True      |          640 | True              |
| 115 | resnet34             |   7.58 |     7.58 |               10 | Memory used: 173.91943359375 MB  | False        |            4 | True      |          640 | True              |
| 116 | resnet34             |  13.95 |    13.97 |               10 | Memory used: 296.39501953125 MB  | False        |            8 | True      |          640 | True              |
| 117 | resnet34             |  26.73 |    26.75 |               10 | Memory used: 540.41943359375 MB  | False        |           16 | True      |          640 | True              |
| 118 | resnet34             |  52.5  |    52.5  |               10 | Memory used: 1028.41943359375 MB | False        |           32 | True      |          640 | True              |
| 119 | resnet34             | 103.46 |   103.49 |                1 | Memory used: 2002.41943359375 MB | False        |           64 | True      |          640 | True              |
| 120 | resnext50_32x4d      |   5.49 |     5.51 |              100 | Memory used: 221.40234375 MB     | False        |            1 | True      |          640 | True              |
| 121 | resnext50_32x4d      |  15.09 |    15.1  |               10 | Memory used: 281.08984375 MB     | False        |            4 | True      |          640 | True              |
| 122 | resnext50_32x4d      |  28.87 |    28.88 |               10 | Memory used: 428.05859375 MB     | False        |            8 | True      |          640 | True              |
| 123 | resnext50_32x4d      |  55.81 |    55.83 |               10 | Memory used: 794.34423828125 MB  | False        |           16 | True      |          640 | True              |
| 124 | resnext50_32x4d      | 105.86 |   105.86 |                1 | Memory used: 1532.34423828125 MB | False        |           32 | True      |          640 | True              |
| 125 | resnext50_32x4d      | 214.99 |   214.98 |                1 | Memory used: 3006.30908203125 MB | False        |           64 | True      |          640 | True              |