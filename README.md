Dataset format :

### raw_data.mat                    	(training_data for stroke classification)

```
size : 1 x 525
raw_data(i)			(stroke sample)
	type : struct
        raw_data(i).label       (class label of the stroke)
        raw_data(i).xy          (x-y coordinates of the stroke sample., from pen down to pen up)
```

### raw_test_data.mat               	(tesing_data for stroke classification)

```
size : 1 x 105
raw_test_data(i)		(stroke sample)
	type : struct
	raw_test_data(i).label  (class label of the stroke)
	raw_test_data(i).xy     (x-y coordinates of the stroke sample., from pen down to pen up)
```

### multi_stroke_relation_data.mat	(training_data for character classification)

```
size : 1 x 400 
type : struct array
multi_stroke_relation_data(i)			(character sample)
	type : 1 x 37 int vector
	multi_stroke_relation_data(i).label	(character label)
	multi_stroke_relation_data(i).ip_vector	(stroke relation vector of the character)
```

### multi_stroke_relation_test_data.mat	(testing_data for character classification)

```
size : 1 x 400
type : struct array
multi_stroke_relation_test_data(i)			(character sample)
	type : 1 x 37 int vector
	multi_stroke_relation_test_data(i).label	(character label)
	multi_stroke_relation_test_data(i).ip_vector	(stroke relation vector of the character)
```
