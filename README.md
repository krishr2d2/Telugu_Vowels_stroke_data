Dataset format :

raw_data.mat                    (training_data)
    size : 1 x 525
    raw_data(i)                 (stroke sample)
        type : struct
        raw_data(i).label       (class label of the stroke)
        raw_data(i).xy          (x-y coordinates of the stroke sample., from pen down to pen up)


raw_test_data.mat               (tesing_data)
    size : 1 x 105
    raw_test_data(i)            (stroke sample)
        type : struct
        raw_test_data(i).label  (class label of the stroke)
        raw_test_data(i).xy     (x-y coordinates of the stroke sample., from pen down to pen up)


