# Desafio Azure DIO 2 - Reconhecimento facial e transformação de imagens

##Foram testados os recursos de reconhecimento de imagens do Azure
Os arquivos testados estão na pasta inputs e os resultados obtidos na pasta output

###Reconhecimento de pessoas em uma imagem
1-Clique em criar um recurso, Azure ALI services
2-Insira o nome, em Pricing Tier selecione Standard S0 e marque o checkbox
3-Acesse portal.vision.cognitive.azure.com
4-Clique em ver todos recursos e selecione o que criou e marque como default
5-Clique na aba Face, depois em Detect faces in an image
6-Marque a checkbox e teste com sua imagem 
Resultado obtido:
[https://github.com/grapiuna/azure-dio2/blob/a05c05236a2a397c3a6f5706b043b57fd3fcd7ab/output/03.jpg](https://github.com/grapiuna/azure-dio2/blob/a05c05236a2a397c3a6f5706b043b57fd3fcd7ab/output/03.jpg)
Json obtido:
```
[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 64,
      "height": 86,
      "left": 536,
      "top": 270
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 560.8,
        "y": 307.6
      },
      "pupilRight": {
        "x": 587.3,
        "y": 305.9
      },
      "noseTip": {
        "x": 579.4,
        "y": 319.1
      },
      "mouthLeft": {
        "x": 562.4,
        "y": 333
      },
      "mouthRight": {
        "x": 589.3,
        "y": 331.3
      },
      "eyebrowLeftOuter": {
        "x": 549.4,
        "y": 302.7
      },
      "eyebrowLeftInner": {
        "x": 568,
        "y": 299.5
      },
      "eyeLeftOuter": {
        "x": 556,
        "y": 308.1
      },
      "eyeLeftTop": {
        "x": 561.1,
        "y": 306.1
      },
      "eyeLeftBottom": {
        "x": 560.8,
        "y": 308.6
      },
      "eyeLeftInner": {
        "x": 565.3,
        "y": 307.4
      },
      "eyebrowRightInner": {
        "x": 581.4,
        "y": 299.1
      },
      "eyebrowRightOuter": {
        "x": 595.2,
        "y": 299.4
      },
      "eyeRightInner": {
        "x": 583.2,
        "y": 306.5
      },
      "eyeRightTop": {
        "x": 587.2,
        "y": 304.4
      },
      "eyeRightBottom": {
        "x": 587.5,
        "y": 306.9
      },
      "eyeRightOuter": {
        "x": 591.4,
        "y": 305.9
      },
      "noseRootLeft": {
        "x": 571.5,
        "y": 307.5
      },
      "noseRootRight": {
        "x": 579.3,
        "y": 306.9
      },
      "noseLeftAlarTop": {
        "x": 570.7,
        "y": 316.4
      },
      "noseRightAlarTop": {
        "x": 583.1,
        "y": 315.2
      },
      "noseLeftAlarOutTip": {
        "x": 567.9,
        "y": 321.5
      },
      "noseRightAlarOutTip": {
        "x": 586.1,
        "y": 320.2
      },
      "upperLipTop": {
        "x": 578.7,
        "y": 329.8
      },
      "upperLipBottom": {
        "x": 578.3,
        "y": 332
      },
      "underLipTop": {
        "x": 578.5,
        "y": 334.7
      },
      "underLipBottom": {
        "x": 578.8,
        "y": 338.1
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 60,
      "height": 85,
      "left": 662,
      "top": 277
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 681.3,
        "y": 307.9
      },
      "pupilRight": {
        "x": 707.8,
        "y": 313.7
      },
      "noseTip": {
        "x": 695.2,
        "y": 324.3
      },
      "mouthLeft": {
        "x": 675.6,
        "y": 332.9
      },
      "mouthRight": {
        "x": 704,
        "y": 338.7
      },
      "eyebrowLeftOuter": {
        "x": 672.1,
        "y": 302.1
      },
      "eyebrowLeftInner": {
        "x": 690.3,
        "y": 304.3
      },
      "eyeLeftOuter": {
        "x": 676.8,
        "y": 307.3
      },
      "eyeLeftTop": {
        "x": 681.9,
        "y": 306.7
      },
      "eyeLeftBottom": {
        "x": 681.1,
        "y": 308.8
      },
      "eyeLeftInner": {
        "x": 685.7,
        "y": 308.9
      },
      "eyebrowRightInner": {
        "x": 703,
        "y": 307.3
      },
      "eyebrowRightOuter": {
        "x": 717.3,
        "y": 311.5
      },
      "eyeRightInner": {
        "x": 703.6,
        "y": 313.1
      },
      "eyeRightTop": {
        "x": 708,
        "y": 312.4
      },
      "eyeRightBottom": {
        "x": 707.6,
        "y": 314.6
      },
      "eyeRightOuter": {
        "x": 711.8,
        "y": 314.8
      },
      "noseRootLeft": {
        "x": 691.4,
        "y": 311
      },
      "noseRootRight": {
        "x": 699.4,
        "y": 312.7
      },
      "noseLeftAlarTop": {
        "x": 688.3,
        "y": 318.8
      },
      "noseRightAlarTop": {
        "x": 700.8,
        "y": 321.2
      },
      "noseLeftAlarOutTip": {
        "x": 684,
        "y": 322.9
      },
      "noseRightAlarOutTip": {
        "x": 702.5,
        "y": 326.7
      },
      "upperLipTop": {
        "x": 692.5,
        "y": 334.1
      },
      "upperLipBottom": {
        "x": 691.6,
        "y": 336.3
      },
      "underLipTop": {
        "x": 690.6,
        "y": 341
      },
      "underLipBottom": {
        "x": 689.8,
        "y": 344.8
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 61,
      "height": 82,
      "left": 74,
      "top": 73
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 83.4,
        "y": 104.7
      },
      "pupilRight": {
        "x": 109.3,
        "y": 105.1
      },
      "noseTip": {
        "x": 91.1,
        "y": 125.5
      },
      "mouthLeft": {
        "x": 87.8,
        "y": 135.3
      },
      "mouthRight": {
        "x": 110.9,
        "y": 135.1
      },
      "eyebrowLeftOuter": {
        "x": 74.2,
        "y": 96.9
      },
      "eyebrowLeftInner": {
        "x": 86.8,
        "y": 99.1
      },
      "eyeLeftOuter": {
        "x": 79.4,
        "y": 104.4
      },
      "eyeLeftTop": {
        "x": 83.4,
        "y": 102.9
      },
      "eyeLeftBottom": {
        "x": 83.2,
        "y": 106.5
      },
      "eyeLeftInner": {
        "x": 87.5,
        "y": 105.2
      },
      "eyebrowRightInner": {
        "x": 98.9,
        "y": 99
      },
      "eyebrowRightOuter": {
        "x": 120.2,
        "y": 98.3
      },
      "eyeRightInner": {
        "x": 104.9,
        "y": 105.5
      },
      "eyeRightTop": {
        "x": 108.8,
        "y": 102.9
      },
      "eyeRightBottom": {
        "x": 109.3,
        "y": 107
      },
      "eyeRightOuter": {
        "x": 114.3,
        "y": 105.1
      },
      "noseRootLeft": {
        "x": 90.9,
        "y": 106.7
      },
      "noseRootRight": {
        "x": 97.6,
        "y": 107
      },
      "noseLeftAlarTop": {
        "x": 88.1,
        "y": 118.7
      },
      "noseRightAlarTop": {
        "x": 100.4,
        "y": 118.6
      },
      "noseLeftAlarOutTip": {
        "x": 86.5,
        "y": 124.2
      },
      "noseRightAlarOutTip": {
        "x": 103.7,
        "y": 124.7
      },
      "upperLipTop": {
        "x": 95.9,
        "y": 134.5
      },
      "upperLipBottom": {
        "x": 96.2,
        "y": 136.6
      },
      "underLipTop": {
        "x": 96.5,
        "y": 139.2
      },
      "underLipBottom": {
        "x": 96.8,
        "y": 143
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 59,
      "height": 82,
      "left": 219,
      "top": 50
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 234.1,
        "y": 86.5
      },
      "pupilRight": {
        "x": 261.4,
        "y": 83.2
      },
      "noseTip": {
        "x": 248.8,
        "y": 98.6
      },
      "mouthLeft": {
        "x": 239.1,
        "y": 112.8
      },
      "mouthRight": {
        "x": 262,
        "y": 110.1
      },
      "eyebrowLeftOuter": {
        "x": 224.9,
        "y": 81.3
      },
      "eyebrowLeftInner": {
        "x": 240,
        "y": 79.6
      },
      "eyeLeftOuter": {
        "x": 229.3,
        "y": 87.2
      },
      "eyeLeftTop": {
        "x": 234.4,
        "y": 85.1
      },
      "eyeLeftBottom": {
        "x": 233.8,
        "y": 87.6
      },
      "eyeLeftInner": {
        "x": 238.9,
        "y": 86.1
      },
      "eyebrowRightInner": {
        "x": 253.1,
        "y": 78.3
      },
      "eyebrowRightOuter": {
        "x": 269.7,
        "y": 76.8
      },
      "eyeRightInner": {
        "x": 256.8,
        "y": 84
      },
      "eyeRightTop": {
        "x": 260.8,
        "y": 81.7
      },
      "eyeRightBottom": {
        "x": 261.7,
        "y": 84.2
      },
      "eyeRightOuter": {
        "x": 266.3,
        "y": 82.7
      },
      "noseRootLeft": {
        "x": 243.5,
        "y": 86.7
      },
      "noseRootRight": {
        "x": 251.5,
        "y": 85.7
      },
      "noseLeftAlarTop": {
        "x": 242.5,
        "y": 95.5
      },
      "noseRightAlarTop": {
        "x": 254.6,
        "y": 94
      },
      "noseLeftAlarOutTip": {
        "x": 240.5,
        "y": 100.8
      },
      "noseRightAlarOutTip": {
        "x": 257.7,
        "y": 99.1
      },
      "upperLipTop": {
        "x": 250.8,
        "y": 109.6
      },
      "upperLipBottom": {
        "x": 250.4,
        "y": 111.5
      },
      "underLipTop": {
        "x": 250.5,
        "y": 113.1
      },
      "underLipBottom": {
        "x": 251,
        "y": 116.2
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 59,
      "height": 83,
      "left": 326,
      "top": 49
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 340.8,
        "y": 85.2
      },
      "pupilRight": {
        "x": 366.6,
        "y": 84
      },
      "noseTip": {
        "x": 353.4,
        "y": 97.8
      },
      "mouthLeft": {
        "x": 341.9,
        "y": 108.1
      },
      "mouthRight": {
        "x": 368.3,
        "y": 106.6
      },
      "eyebrowLeftOuter": {
        "x": 333.2,
        "y": 78.6
      },
      "eyebrowLeftInner": {
        "x": 346.2,
        "y": 78.3
      },
      "eyeLeftOuter": {
        "x": 336.1,
        "y": 85.3
      },
      "eyeLeftTop": {
        "x": 341.3,
        "y": 84.1
      },
      "eyeLeftBottom": {
        "x": 340.2,
        "y": 86.1
      },
      "eyeLeftInner": {
        "x": 345.5,
        "y": 85.3
      },
      "eyebrowRightInner": {
        "x": 359.4,
        "y": 78
      },
      "eyebrowRightOuter": {
        "x": 375,
        "y": 77.9
      },
      "eyeRightInner": {
        "x": 362,
        "y": 84.6
      },
      "eyeRightTop": {
        "x": 366,
        "y": 82.7
      },
      "eyeRightBottom": {
        "x": 366.9,
        "y": 85
      },
      "eyeRightOuter": {
        "x": 371.5,
        "y": 83.6
      },
      "noseRootLeft": {
        "x": 349.5,
        "y": 86.2
      },
      "noseRootRight": {
        "x": 356.9,
        "y": 85.8
      },
      "noseLeftAlarTop": {
        "x": 347.4,
        "y": 94.4
      },
      "noseRightAlarTop": {
        "x": 359.8,
        "y": 93.6
      },
      "noseLeftAlarOutTip": {
        "x": 345.2,
        "y": 98.7
      },
      "noseRightAlarOutTip": {
        "x": 362.8,
        "y": 98
      },
      "upperLipTop": {
        "x": 355.2,
        "y": 106.8
      },
      "upperLipBottom": {
        "x": 354.7,
        "y": 108.4
      },
      "underLipTop": {
        "x": 354.8,
        "y": 112.1
      },
      "underLipBottom": {
        "x": 355.1,
        "y": 115.1
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 60,
      "height": 79,
      "left": 526,
      "top": 54
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 541.8,
        "y": 78.7
      },
      "pupilRight": {
        "x": 568.1,
        "y": 78.3
      },
      "noseTip": {
        "x": 554.4,
        "y": 93.9
      },
      "mouthLeft": {
        "x": 540.6,
        "y": 104.2
      },
      "mouthRight": {
        "x": 569.8,
        "y": 104
      },
      "eyebrowLeftOuter": {
        "x": 532.1,
        "y": 73.3
      },
      "eyebrowLeftInner": {
        "x": 547.8,
        "y": 72.3
      },
      "eyeLeftOuter": {
        "x": 537.5,
        "y": 78.9
      },
      "eyeLeftTop": {
        "x": 542,
        "y": 77.8
      },
      "eyeLeftBottom": {
        "x": 541.7,
        "y": 79.4
      },
      "eyeLeftInner": {
        "x": 546,
        "y": 78.9
      },
      "eyebrowRightInner": {
        "x": 561.3,
        "y": 72.1
      },
      "eyebrowRightOuter": {
        "x": 577.9,
        "y": 72.9
      },
      "eyeRightInner": {
        "x": 563.9,
        "y": 78.6
      },
      "eyeRightTop": {
        "x": 567.8,
        "y": 77.1
      },
      "eyeRightBottom": {
        "x": 568.2,
        "y": 79
      },
      "eyeRightOuter": {
        "x": 572.4,
        "y": 78.3
      },
      "noseRootLeft": {
        "x": 550.8,
        "y": 79.7
      },
      "noseRootRight": {
        "x": 558.4,
        "y": 79.7
      },
      "noseLeftAlarTop": {
        "x": 548.5,
        "y": 89.1
      },
      "noseRightAlarTop": {
        "x": 561,
        "y": 88.9
      },
      "noseLeftAlarOutTip": {
        "x": 545.4,
        "y": 93.8
      },
      "noseRightAlarOutTip": {
        "x": 564,
        "y": 94
      },
      "upperLipTop": {
        "x": 555.3,
        "y": 103
      },
      "upperLipBottom": {
        "x": 554.9,
        "y": 105.1
      },
      "underLipTop": {
        "x": 555,
        "y": 110.1
      },
      "underLipBottom": {
        "x": 554.9,
        "y": 113.7
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 59,
      "height": 79,
      "left": 205,
      "top": 271
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 222.5,
        "y": 301.2
      },
      "pupilRight": {
        "x": 248.9,
        "y": 303.4
      },
      "noseTip": {
        "x": 235.1,
        "y": 315.8
      },
      "mouthLeft": {
        "x": 219.3,
        "y": 325.3
      },
      "mouthRight": {
        "x": 248,
        "y": 327.7
      },
      "eyebrowLeftOuter": {
        "x": 214.3,
        "y": 294.4
      },
      "eyebrowLeftInner": {
        "x": 229.6,
        "y": 295.1
      },
      "eyeLeftOuter": {
        "x": 217.8,
        "y": 300.9
      },
      "eyeLeftTop": {
        "x": 223,
        "y": 300.3
      },
      "eyeLeftBottom": {
        "x": 222.1,
        "y": 301.8
      },
      "eyeLeftInner": {
        "x": 227.1,
        "y": 301.8
      },
      "eyebrowRightInner": {
        "x": 243,
        "y": 296.4
      },
      "eyebrowRightOuter": {
        "x": 258.3,
        "y": 298.7
      },
      "eyeRightInner": {
        "x": 244.4,
        "y": 303.3
      },
      "eyeRightTop": {
        "x": 248.7,
        "y": 302.3
      },
      "eyeRightBottom": {
        "x": 249,
        "y": 304.1
      },
      "eyeRightOuter": {
        "x": 253.5,
        "y": 303.8
      },
      "noseRootLeft": {
        "x": 231.7,
        "y": 303.1
      },
      "noseRootRight": {
        "x": 239.5,
        "y": 303.6
      },
      "noseLeftAlarTop": {
        "x": 228.8,
        "y": 311.2
      },
      "noseRightAlarTop": {
        "x": 241.6,
        "y": 312.1
      },
      "noseLeftAlarOutTip": {
        "x": 225.4,
        "y": 315.3
      },
      "noseRightAlarOutTip": {
        "x": 244.1,
        "y": 317
      },
      "upperLipTop": {
        "x": 234.8,
        "y": 324.9
      },
      "upperLipBottom": {
        "x": 234.1,
        "y": 327
      },
      "underLipTop": {
        "x": 233.4,
        "y": 333.3
      },
      "underLipBottom": {
        "x": 233.1,
        "y": 337
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 61,
      "height": 77,
      "left": 318,
      "top": 271
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 333.1,
        "y": 303.4
      },
      "pupilRight": {
        "x": 362.9,
        "y": 301.4
      },
      "noseTip": {
        "x": 347.8,
        "y": 314.5
      },
      "mouthLeft": {
        "x": 334,
        "y": 326.6
      },
      "mouthRight": {
        "x": 364.7,
        "y": 324.4
      },
      "eyebrowLeftOuter": {
        "x": 322.7,
        "y": 299.5
      },
      "eyebrowLeftInner": {
        "x": 339.5,
        "y": 297.2
      },
      "eyeLeftOuter": {
        "x": 328.3,
        "y": 304.1
      },
      "eyeLeftTop": {
        "x": 333.1,
        "y": 301.7
      },
      "eyeLeftBottom": {
        "x": 332.9,
        "y": 304.7
      },
      "eyeLeftInner": {
        "x": 337.9,
        "y": 303.2
      },
      "eyebrowRightInner": {
        "x": 354.6,
        "y": 296.3
      },
      "eyebrowRightOuter": {
        "x": 373,
        "y": 296.9
      },
      "eyeRightInner": {
        "x": 358.1,
        "y": 302
      },
      "eyeRightTop": {
        "x": 362.7,
        "y": 299.6
      },
      "eyeRightBottom": {
        "x": 363,
        "y": 302.6
      },
      "eyeRightOuter": {
        "x": 367.9,
        "y": 301.4
      },
      "noseRootLeft": {
        "x": 343.2,
        "y": 303.4
      },
      "noseRootRight": {
        "x": 351.7,
        "y": 302.6
      },
      "noseLeftAlarTop": {
        "x": 341.6,
        "y": 311
      },
      "noseRightAlarTop": {
        "x": 354.3,
        "y": 310.3
      },
      "noseLeftAlarOutTip": {
        "x": 338.6,
        "y": 315.8
      },
      "noseRightAlarOutTip": {
        "x": 357.7,
        "y": 314.9
      },
      "upperLipTop": {
        "x": 349.3,
        "y": 324.1
      },
      "upperLipBottom": {
        "x": 348.9,
        "y": 326.2
      },
      "underLipTop": {
        "x": 349.1,
        "y": 329.2
      },
      "underLipBottom": {
        "x": 349.3,
        "y": 332.6
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 58,
      "height": 80,
      "left": 93,
      "top": 284
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 112.7,
        "y": 317.8
      },
      "pupilRight": {
        "x": 138.4,
        "y": 313.6
      },
      "noseTip": {
        "x": 131,
        "y": 330.5
      },
      "mouthLeft": {
        "x": 115.3,
        "y": 342.7
      },
      "mouthRight": {
        "x": 142.7,
        "y": 338.1
      },
      "eyebrowLeftOuter": {
        "x": 102.4,
        "y": 314.6
      },
      "eyebrowLeftInner": {
        "x": 119.3,
        "y": 311.4
      },
      "eyeLeftOuter": {
        "x": 108.1,
        "y": 318.6
      },
      "eyeLeftTop": {
        "x": 112.9,
        "y": 316.5
      },
      "eyeLeftBottom": {
        "x": 112.6,
        "y": 318.7
      },
      "eyeLeftInner": {
        "x": 117.1,
        "y": 317.3
      },
      "eyebrowRightInner": {
        "x": 132.1,
        "y": 309.6
      },
      "eyebrowRightOuter": {
        "x": 145.9,
        "y": 307.5
      },
      "eyeRightInner": {
        "x": 134.3,
        "y": 314.7
      },
      "eyeRightTop": {
        "x": 138.1,
        "y": 312.3
      },
      "eyeRightBottom": {
        "x": 138.8,
        "y": 314.5
      },
      "eyeRightOuter": {
        "x": 142.5,
        "y": 313
      },
      "noseRootLeft": {
        "x": 122.8,
        "y": 317.7
      },
      "noseRootRight": {
        "x": 130.6,
        "y": 316.5
      },
      "noseLeftAlarTop": {
        "x": 122.5,
        "y": 326.8
      },
      "noseRightAlarTop": {
        "x": 134.8,
        "y": 324.6
      },
      "noseLeftAlarOutTip": {
        "x": 120.1,
        "y": 331.9
      },
      "noseRightAlarOutTip": {
        "x": 137.9,
        "y": 329
      },
      "upperLipTop": {
        "x": 131.4,
        "y": 339.4
      },
      "upperLipBottom": {
        "x": 131.2,
        "y": 341.6
      },
      "underLipTop": {
        "x": 131.7,
        "y": 346.1
      },
      "underLipBottom": {
        "x": 132.3,
        "y": 349.8
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 60,
      "height": 76,
      "left": 411,
      "top": 279
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 427.7,
        "y": 307.8
      },
      "pupilRight": {
        "x": 455.4,
        "y": 305.9
      },
      "noseTip": {
        "x": 442.9,
        "y": 317.5
      },
      "mouthLeft": {
        "x": 432.8,
        "y": 335.6
      },
      "mouthRight": {
        "x": 455.5,
        "y": 333.7
      },
      "eyebrowLeftOuter": {
        "x": 418.5,
        "y": 303.3
      },
      "eyebrowLeftInner": {
        "x": 434.4,
        "y": 300.6
      },
      "eyeLeftOuter": {
        "x": 423,
        "y": 308.7
      },
      "eyeLeftTop": {
        "x": 427.9,
        "y": 306.1
      },
      "eyeLeftBottom": {
        "x": 427.5,
        "y": 309
      },
      "eyeLeftInner": {
        "x": 432.5,
        "y": 307.5
      },
      "eyebrowRightInner": {
        "x": 447.7,
        "y": 300.1
      },
      "eyebrowRightOuter": {
        "x": 464.3,
        "y": 301.1
      },
      "eyeRightInner": {
        "x": 450.9,
        "y": 306.4
      },
      "eyeRightTop": {
        "x": 455,
        "y": 304.1
      },
      "eyeRightBottom": {
        "x": 455.6,
        "y": 307
      },
      "eyeRightOuter": {
        "x": 460.1,
        "y": 306
      },
      "noseRootLeft": {
        "x": 437.6,
        "y": 307.6
      },
      "noseRootRight": {
        "x": 445.8,
        "y": 306.8
      },
      "noseLeftAlarTop": {
        "x": 436.5,
        "y": 316
      },
      "noseRightAlarTop": {
        "x": 448.6,
        "y": 314.8
      },
      "noseLeftAlarOutTip": {
        "x": 434.3,
        "y": 321.7
      },
      "noseRightAlarOutTip": {
        "x": 451.7,
        "y": 320.6
      },
      "upperLipTop": {
        "x": 444.6,
        "y": 330.8
      },
      "upperLipBottom": {
        "x": 444.3,
        "y": 333
      },
      "underLipTop": {
        "x": 444.4,
        "y": 334.3
      },
      "underLipBottom": {
        "x": 444.7,
        "y": 337.2
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 59,
      "height": 74,
      "left": 436,
      "top": 55
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 458.4,
        "y": 81
      },
      "pupilRight": {
        "x": 482.5,
        "y": 91.4
      },
      "noseTip": {
        "x": 467.9,
        "y": 95.3
      },
      "mouthLeft": {
        "x": 450.1,
        "y": 104.6
      },
      "mouthRight": {
        "x": 471.7,
        "y": 113.9
      },
      "eyebrowLeftOuter": {
        "x": 451.9,
        "y": 73.6
      },
      "eyebrowLeftInner": {
        "x": 467.1,
        "y": 78.3
      },
      "eyeLeftOuter": {
        "x": 454,
        "y": 79.8
      },
      "eyeLeftTop": {
        "x": 459.2,
        "y": 79.8
      },
      "eyeLeftBottom": {
        "x": 457.8,
        "y": 81.7
      },
      "eyeLeftInner": {
        "x": 462.5,
        "y": 82.8
      },
      "eyebrowRightInner": {
        "x": 478.7,
        "y": 83.5
      },
      "eyebrowRightOuter": {
        "x": 491.8,
        "y": 91.2
      },
      "eyeRightInner": {
        "x": 478.6,
        "y": 89.9
      },
      "eyeRightTop": {
        "x": 483,
        "y": 89.9
      },
      "eyeRightBottom": {
        "x": 482.3,
        "y": 92.2
      },
      "eyeRightOuter": {
        "x": 486.4,
        "y": 93.5
      },
      "noseRootLeft": {
        "x": 467,
        "y": 85.2
      },
      "noseRootRight": {
        "x": 474.3,
        "y": 88.1
      },
      "noseLeftAlarTop": {
        "x": 463,
        "y": 91
      },
      "noseRightAlarTop": {
        "x": 473.4,
        "y": 95.4
      },
      "noseLeftAlarOutTip": {
        "x": 458.6,
        "y": 94.3
      },
      "noseRightAlarOutTip": {
        "x": 473.8,
        "y": 101.1
      },
      "upperLipTop": {
        "x": 463.6,
        "y": 105.7
      },
      "upperLipBottom": {
        "x": 462.2,
        "y": 107.8
      },
      "underLipTop": {
        "x": 460.6,
        "y": 111.4
      },
      "underLipBottom": {
        "x": 459.3,
        "y": 114.6
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  },
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 56,
      "height": 78,
      "left": 635,
      "top": 52
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 648.8,
        "y": 83.1
      },
      "pupilRight": {
        "x": 674.2,
        "y": 81.3
      },
      "noseTip": {
        "x": 661.9,
        "y": 95.8
      },
      "mouthLeft": {
        "x": 651,
        "y": 108.4
      },
      "mouthRight": {
        "x": 676.2,
        "y": 106.4
      },
      "eyebrowLeftOuter": {
        "x": 641.2,
        "y": 76.3
      },
      "eyebrowLeftInner": {
        "x": 654.1,
        "y": 75.2
      },
      "eyeLeftOuter": {
        "x": 644.1,
        "y": 83.4
      },
      "eyeLeftTop": {
        "x": 649.3,
        "y": 81.5
      },
      "eyeLeftBottom": {
        "x": 648.2,
        "y": 84.4
      },
      "eyeLeftInner": {
        "x": 653.6,
        "y": 83.1
      },
      "eyebrowRightInner": {
        "x": 667.2,
        "y": 74.7
      },
      "eyebrowRightOuter": {
        "x": 682.3,
        "y": 74.9
      },
      "eyeRightInner": {
        "x": 669.6,
        "y": 82.1
      },
      "eyeRightTop": {
        "x": 673.5,
        "y": 79.5
      },
      "eyeRightBottom": {
        "x": 674.6,
        "y": 82.6
      },
      "eyeRightOuter": {
        "x": 679.2,
        "y": 80.8
      },
      "noseRootLeft": {
        "x": 657.6,
        "y": 84
      },
      "noseRootRight": {
        "x": 665,
        "y": 83.3
      },
      "noseLeftAlarTop": {
        "x": 655.7,
        "y": 92.8
      },
      "noseRightAlarTop": {
        "x": 668.3,
        "y": 91.7
      },
      "noseLeftAlarOutTip": {
        "x": 653.7,
        "y": 97.7
      },
      "noseRightAlarOutTip": {
        "x": 671.2,
        "y": 96.5
      },
      "upperLipTop": {
        "x": 663.9,
        "y": 105.9
      },
      "upperLipBottom": {
        "x": 663.4,
        "y": 107.8
      },
      "underLipTop": {
        "x": 663.7,
        "y": 112.1
      },
      "underLipBottom": {
        "x": 664,
        "y": 115.3
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  }
]
```

###Adicionar legenda para imagem
1-Acesse portal.vision.cognitive.azure.com
2-Clique Image analysis e Add captions to images
3-Marque a checkbox e teste com sua imagem 
[https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1"](https://github.com/grapiuna/azure-dio2/blob/a05c05236a2a397c3a6f5706b043b57fd3fcd7ab/output/01.jpg)
Json obtido:
```
{
  "apim-request-id": "ccc6ba7a-10e0-4ffb-9bdb-f60ab17b9069",
  "content-length": "163",
  "content-type": "application/json; charset=utf-8",
  "modelVersion": "2023-10-01",
  "captionResult": {
    "text": "a large crowd of people at a concert",
    "confidence": 0.7926273345947266
  },
  "metadata": {
    "width": 678,
    "height": 452
  }
}
```

###Analisar documentos
1-Acesse portal.vision.cognitive.azure.com
2-Clique Optical character recognition e extract text from image
3-Marque a checkbox e teste com sua imagem 
[https://github.com/grapiuna/azure-dio2/blob/a05c05236a2a397c3a6f5706b043b57fd3fcd7ab/output/02.jpeg](https://github.com/grapiuna/azure-dio2/blob/a05c05236a2a397c3a6f5706b043b57fd3fcd7ab/output/02.jpeg)https://github.com/grapiuna/azure-dio2/blob/a05c05236a2a397c3a6f5706b043b57fd3fcd7ab/output/02.jpeg
Json obtido:
```
[
  {
    "lines": [
      {
        "text": "DOR",
        "boundingPolygon": [
          {
            "x": 136,
            "y": 22
          },
          {
            "x": 167,
            "y": 28
          },
          {
            "x": 166,
            "y": 40
          },
          {
            "x": 136,
            "y": 36
          }
        ],
        "words": [
          {
            "text": "DOR",
            "boundingPolygon": [
              {
                "x": 138,
                "y": 22
              },
              {
                "x": 163,
                "y": 26
              },
              {
                "x": 161,
                "y": 40
              },
              {
                "x": 136,
                "y": 36
              }
            ],
            "confidence": 0.993
          }
        ]
      },
      {
        "text": "CAPITAL",
        "boundingPolygon": [
          {
            "x": 58,
            "y": 45
          },
          {
            "x": 223,
            "y": 44
          },
          {
            "x": 224,
            "y": 80
          },
          {
            "x": 58,
            "y": 83
          }
        ],
        "words": [
          {
            "text": "CAPITAL",
            "boundingPolygon": [
              {
                "x": 66,
                "y": 46
              },
              {
                "x": 211,
                "y": 45
              },
              {
                "x": 211,
                "y": 81
              },
              {
                "x": 65,
                "y": 82
              }
            ],
            "confidence": 0.688
          }
        ]
      },
      {
        "text": "AFRO",
        "boundingPolygon": [
          {
            "x": 52,
            "y": 87
          },
          {
            "x": 204,
            "y": 86
          },
          {
            "x": 204,
            "y": 132
          },
          {
            "x": 52,
            "y": 135
          }
        ],
        "words": [
          {
            "text": "AFRO",
            "boundingPolygon": [
              {
                "x": 57,
                "y": 87
              },
              {
                "x": 190,
                "y": 87
              },
              {
                "x": 191,
                "y": 132
              },
              {
                "x": 56,
                "y": 136
              }
            ],
            "confidence": 0.954
          }
        ]
      },
      {
        "text": "2024",
        "boundingPolygon": [
          {
            "x": 122,
            "y": 140
          },
          {
            "x": 148,
            "y": 140
          },
          {
            "x": 147,
            "y": 150
          },
          {
            "x": 122,
            "y": 150
          }
        ],
        "words": [
          {
            "text": "2024",
            "boundingPolygon": [
              {
                "x": 124,
                "y": 140
              },
              {
                "x": 146,
                "y": 140
              },
              {
                "x": 146,
                "y": 150
              },
              {
                "x": 124,
                "y": 150
              }
            ],
            "confidence": 0.99
          }
        ]
      },
      {
        "text": "CARNAVAL",
        "boundingPolygon": [
          {
            "x": 102,
            "y": 148
          },
          {
            "x": 169,
            "y": 147
          },
          {
            "x": 170,
            "y": 163
          },
          {
            "x": 102,
            "y": 165
          }
        ],
        "words": [
          {
            "text": "CARNAVAL",
            "boundingPolygon": [
              {
                "x": 105,
                "y": 149
              },
              {
                "x": 166,
                "y": 148
              },
              {
                "x": 166,
                "y": 162
              },
              {
                "x": 104,
                "y": 162
              }
            ],
            "confidence": 0.959
          }
        ]
      }
    ]
  }
]
```
