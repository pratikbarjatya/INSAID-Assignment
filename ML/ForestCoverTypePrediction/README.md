# Forest Cover Type Prediction
The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. Each observation is a 30m x 30m patch.

## Problem Statment - You are asked to predict an integer classification for the forest cover type.
The seven types are:

1 - Spruce/Fir
2 - Lodgepole Pine
3 - Ponderosa Pine
4 - Cottonwood/Willow
5 - Aspen
6 - Douglas-fir
7 - Krummholz The set (15120 observations) contains both features and the Cover_Type.

## Data Fields
Elevation - Elevation in meters
Aspect - Aspect in degrees azimuth 
Slope - Slope in degrees
Horizontal_Distance_To_Hydrology - Horz Dist to nearest surface water features
Vertical_Distance_To_Hydrology - Vert Dist to nearest surface water features
Horizontal_Distance_To_Roadways - Horz Dist to nearest roadway
Hillshade_9am (0 to 255 index) - Hillshade index at 9am, summer solstice
Hillshade_Noon (0 to 255 index) - Hillshade index at noon, summer solstice
Hillshade_3pm (0 to 255 index) - Hillshade index at 3pm, summer solstice
Horizontal_Distance_To_Fire_Points - Horz Dist to nearest wildfire ignition points
Wilderness_Area (4 binary columns, 0 = absence or 1 = presence) - Wilderness area designation
Soil_Type (40 binary columns, 0 = absence or 1 = presence) - Soil Type designation
Cover_Type (7 types, integers 1 to 7) - Forest Cover Type designation

## CONCLUSION

Accuracy with SupportVectorClassifier 0.7984457671957672
Accuracy with ExtraTreesClassifier 0.8022486772486772
Accuracy with RandomForestClassifier 0.8492972717609543

## FUTURE SCOPE

PCA - SVM classifier would perform better with compression techniques like PCA
