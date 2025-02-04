# Annotation File Format

## Disclaimer

The Cell Locator annotation format is non-standard and exists purely as
an implementation detail. While structural changes will be documented below,
the file organization may change from version to version without notice.

We mean it.

## Versions

## 0.1.0 (2020-09-18), Unversioned (2020-09-18)

Annotation files generated with Cell-Locator [0.1.0-2020-09-18](https://github.com/BICCN/cell-locator/releases/tag/0.1.0-2020-09-18) do not include the `version` key.
```json
{
    "version": "0.1.0+2020.09.18",
    "markups": [
        {
            "markup": {
                "type": "ClosedCurve",
                "coordinateSystem": "LPS",
                "controlPoints": [
                    {
                        "id": "1",
                        "position": [
                            -7725.476777936878,
                            5071.924649397559,
                            -2858.6838622146615
                        ],
                        "orientation": [
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            1.0
                        ]
                    },
                    {
                        "id": "2",
                        "position": [
                            -8785.61316343005,
                            5514.035987881592,
                            -4251.158410257692
                        ],
                        "orientation": [
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            1.0
                        ]
                    },
                    {
                        "id": "3",
                        "position": [
                            -7732.355384361564,
                            5984.77667260136,
                            -4339.759187924226
                        ],
                        "orientation": [
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            1.0
                        ]
                    },
                    {
                        "id": "4",
                        "position": [
                            -6980.525470132225,
                            5682.868336976309,
                            -3371.0529631232225
                        ],
                        "orientation": [
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            1.0
                        ]
                    },
                    {
                        "id": "5",
                        "position": [
                            -6735.759199784232,
                            5461.593738502808,
                            -2856.7326570107934
                        ],
                        "orientation": [
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            -1.0,
                            0.0,
                            0.0,
                            0.0,
                            1.0
                        ]
                    }
                ]
            },
            "name": "Annotation",
            "orientation": [
                0.9423723483536421,
                -0.10260749019479301,
                -0.3184431817677528,
                5686.499999999999,
                0.32619099971630533,
                0.49341126738558755,
                0.8063155417831328,
                -6574.999999999999,
                -0.07438943985890348,
                0.863722770437872,
                -0.49844677455532305,
                -3987.4999999999995,
                0.0,
                0.0,
                0.0,
                1.0
            ],
            "representationType": "spline",
            "thickness": 50
        }
    ],
    "currentId": 0,
    "referenceView": "Coronal",
    "ontology": "Structure",
    "stepSize": 24.999999999999996,
    "cameraPosition": [
        5864.945206940424,
        -50233.77100882346,
        -4015.7997990419617
    ],
    "cameraViewUp": [
        0.0,
        0.0,
        1.0
    ]
}
```

## Unversioned (2020-08-26)

```json
{
    "markups": [
        {
            "markup": {
                "type": "ClosedCurve",
                "coordinateSystem": "LPS",
                "locked": false,
                "labelFormat": "%N-%d",
                "controlPoints": [
                    {
                        "id": "1",
                        "label": "MarkupsClosedCurve-1",
                        "description": "",
                        "associatedNodeID": "vtkMRMLScalarVolumeNode1",
                        "position": [
                            -7725.476777936878,
                            5071.924649397559,
                            -2858.6838622146615
                        ],
                        "orientation": [
                            -1,
                            0,
                            0,
                            0,
                            -1,
                            0,
                            0,
                            0,
                            1
                        ],
                        "selected": true,
                        "locked": false,
                        "visibility": true,
                        "positionStatus": "defined"
                    },
                    {
                        "id": "2",
                        "label": "MarkupsClosedCurve-2",
                        "description": "",
                        "associatedNodeID": "vtkMRMLScalarVolumeNode1",
                        "position": [
                            -8785.61316343005,
                            5514.035987881592,
                            -4251.158410257692
                        ],
                        "orientation": [
                            -1,
                            0,
                            0,
                            0,
                            -1,
                            0,
                            0,
                            0,
                            1
                        ],
                        "selected": true,
                        "locked": false,
                        "visibility": true,
                        "positionStatus": "defined"
                    },
                    {
                        "id": "3",
                        "label": "MarkupsClosedCurve-3",
                        "description": "",
                        "associatedNodeID": "vtkMRMLScalarVolumeNode1",
                        "position": [
                            -7732.355384361564,
                            5984.77667260136,
                            -4339.759187924226
                        ],
                        "orientation": [
                            -1,
                            0,
                            0,
                            0,
                            -1,
                            0,
                            0,
                            0,
                            1
                        ],
                        "selected": true,
                        "locked": false,
                        "visibility": true,
                        "positionStatus": "defined"
                    },
                    {
                        "id": "4",
                        "label": "MarkupsClosedCurve-4",
                        "description": "",
                        "associatedNodeID": "vtkMRMLScalarVolumeNode1",
                        "position": [
                            -6980.525470132225,
                            5682.868336976309,
                            -3371.0529631232225
                        ],
                        "orientation": [
                            -1,
                            0,
                            0,
                            0,
                            -1,
                            0,
                            0,
                            0,
                            1
                        ],
                        "selected": true,
                        "locked": false,
                        "visibility": true,
                        "positionStatus": "defined"
                    },
                    {
                        "id": "5",
                        "label": "MarkupsClosedCurve-5",
                        "description": "",
                        "associatedNodeID": "vtkMRMLScalarVolumeNode1",
                        "position": [
                            -6735.759199784232,
                            5461.593738502808,
                            -2856.7326570107934
                        ],
                        "orientation": [
                            -1,
                            0,
                            0,
                            0,
                            -1,
                            0,
                            0,
                            0,
                            1
                        ],
                        "selected": true,
                        "locked": false,
                        "visibility": true,
                        "positionStatus": "defined"
                    }
                ],
                "display": {
                    "visibility": true,
                    "opacity": 1,
                    "color": [
                        0.4,
                        1,
                        1
                    ],
                    "selectedColor": [
                        1,
                        0.5000076295109483,
                        0.5000076295109483
                    ],
                    "propertiesLabelVisibility": true,
                    "pointLabelsVisibility": false,
                    "textScale": 3,
                    "glyphType": "Sphere3D",
                    "glyphScale": 1,
                    "glyphSize": 5,
                    "useGlyphScale": true,
                    "sliceProjection": false,
                    "sliceProjectionUseFiducialColor": true,
                    "sliceProjectionOutlinedBehindSlicePlane": false,
                    "sliceProjectionColor": [
                        1,
                        1,
                        1
                    ],
                    "sliceProjectionOpacity": 0.6,
                    "lineThickness": 0.2,
                    "lineColorFadingStart": 1,
                    "lineColorFadingEnd": 10,
                    "lineColorFadingSaturation": 1,
                    "lineColorFadingHueOffset": 0,
                    "handlesInteractive": false,
                    "snapMode": "toVisibleSurface"
                }
            },
            "orientation": [
                0.9423723483536421,
                -0.10260749019479301,
                -0.3184431817677528,
                5686.499999999999,
                0.32619099971630533,
                0.49341126738558755,
                0.8063155417831328,
                -6574.999999999999,
                -0.07438943985890348,
                0.863722770437872,
                -0.49844677455532305,
                -3987.4999999999995,
                0,
                0,
                0,
                1
            ],
            "representationType": "spline",
            "thickness": 50
        }
    ],
    "currentId": 0,
    "referenceView": "Coronal",
    "ontology": "Structure",
    "stepSize": 24.999999999999996,
    "cameraPosition": [
        5864.945206940424,
        -50233.77100882346,
        -4015.7997990419617
    ],
    "cameraViewUp": [
        0,
        0,
        1
    ]
}
```

## Unversioned (2019-01-26)

```json
{
    "DefaultCameraPosition":[
       5873.05421548901,
       -54260.69374827002,
       -4027.878783549626
    ],
    "DefaultCameraViewUp":[
       0.0,
       0.0,
       1.0
    ],
    "DefaultOntology":"Structure",
    "DefaultReferenceView":"Coronal",
    "DefaultRepresentationType":"spline",
    "DefaultSplineOrientation":[
       -1.0,
       0.0,
       0.0,
       5686.499999999999,
       0.0,
       0.0,
       -1.0,
       -6599.999999999999,
       0.0,
       1.0,
       0.0,
       -3987.4999999999997,
       0.0,
       0.0,
       0.0,
       1.0
    ],
    "DefaultStepSize":24.999999999999998,
    "DefaultThickness":50.0,
    "Locked":0,
    "MarkupLabelFormat":"%N-%d",
    "Markups":[
       {
          "AssociatedNodeID": "vtkMRMLModelNode5",
          "CameraPosition": [
              0.0,
              0.0,
              0.0
          ],
          "CameraViewUp": [
              0.0,
              0.0,
              0.0
          ],
          "Closed": 1,
          "Description": "",
          "ID": "vtkMRMLMarkupsSplinesNode_0",
          "Label": "Annotation-1",
          "Locked": 0,
          "Ontology": "Structure",
          "OrientationWXYZ": [
              0.0,
              0.0,
              0.0,
              1.0
          ],
          "Points": [
              {
                  "x": 7736.406932105033,
                  "y": -6315.297589137253,
                  "z": -1755.7577043808915
              },
              {
                  "x": 8089.826952763821,
                  "y": -6315.297589137253,
                  "z": -1893.3464794555367
              },
              {
                  "x": 8563.263519088907,
                  "y": -6315.297589137253,
                  "z": -950.1244332210372
              },
              {
                  "x": 8233.71868467818,
                  "y": -6315.297589137253,
                  "z": -786.6443712232194
              }
          ],
          "Points_Count": "4",
          "ReferenceView": "Coronal",
          "RepresentationType": "spline",
          "Selected": 1,
          "SplineOrientation": [
              -1.0,
              0.0,
              0.0,
              5658.88223569956,
              0.0,
              0.0,
              -1.0,
              -6315.297589137253,
              0.0,
              1.0,
              0.0,
              -2943.1556456320488,
              0.0,
              0.0,
              0.0,
              1.0
          ],
          "StepSize": 735.0,
          "Thickness": 50.0,
          "Visibility": 1
      }
    ],
    "Markups_Count":0,
    "TextList":[
       null
    ],
    "TextList_Count":0
 }
```
