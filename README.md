# RMS-ICP

## Runtime test

Test are conducted on 13 different samples taken from combined(standard ASL, and local) dataset.

![Runtime test results](./imgs/chart.png 'Runtime test over 13 samples from combined(standard and local) dataset.')

## Robustness Test Results

All of the algorithms are tested on `10` random samples with different overlaps type(High and Low) from each of the ASL `Apartment`, `Stairs`, and `Gazebo Summer` subsets. For each sample `5` different randomly generated transforms are used to test the registration. The results are given here:

![Overall Robustness test (`2 * 3 * 10 * 5` : `samples * transforms`)](./imgs/Overall.png 'Overall Robustness test (`2 * 10 * 5` : `samples * transforms`)')

![Robustness test on ASL Stairs subset (`10 * 5[H] + 10 * 5[L]` : `samples * transforms`)](./imgs/Stairs.png 'Robustness test on ASL Stairs subset (`10 * 5[H] + 10 * 5[L]` : `samples * transforms`)')

![Robustness test on ASL Apartment subset (`10 * 5[H] + 10 * 5[L]` : `samples * transforms`)](./imgs/Apartment.png 'Robustness test on ASL Apartment subset (`10 * 5[H] + 10 * 5[L]` : `samples * transforms`)')

![Robustness test on ASL Gazebo Summer subset (`10 * 5[H] + 10 * 5[L]` : `samples * transforms`)](./imgs/Gazebo.png 'Robustness test on ASL Gazebo Summer subset (`10 * 5[H] + 10 * 5[L]` : `samples * transforms`)')

## Iteration Speed Test Results

### Sample1
![](./itr_results/iter_comp501/drawing.png ' ')

![](./itr_results/iter_comp501/new_smoothen_err2.png ' ')

### Sample2
![](./itr_results/iter_comp502/drawing.png ' ')

![](./itr_results/iter_comp502/new_smoothen_err2.png ' ')

### Sample3
![](./itr_results/iter_comp503/drawing.png ' ')

![](./itr_results/iter_comp503/new_smoothen_err2.png ' ')

### Sample4
![](./itr_results/iter_comp504/drawing.png ' ')

![](./itr_results/iter_comp504/new_smoothen_err2.png ' ')

### Sample5
![](./itr_results/iter_comp505/drawing.png ' ')

![](./itr_results/iter_comp505/new_smoothen_err2.png ' ')

### Sample6
![](./itr_results/iter_comp506/drawing.png ' ')

![](./itr_results/iter_comp506/new_smoothen_err2.png ' ')

### Sample7
![](./itr_results/iter_comp507/drawing.png ' ')

![](./itr_results/iter_comp507/new_smoothen_err2.png ' ')

### Sample8
![](./itr_results/iter_comp508/drawing.png ' ')

![](./itr_results/iter_comp508/new_smoothen_err2.png ' ')

### Sample9
![](./itr_results/iter_comp509/drawing.png ' ')

![](./itr_results/iter_comp509/new_smoothen_err2.png ' ')

### Sample10
![](./itr_results/iter_comp510/drawing.png ' ')

![](./itr_results/iter_comp510/new_smoothen_err2.png ' ')

### Sample11
![](./itr_results/iter_comp511/drawing.png ' ')

![](./itr_results/iter_comp511/new_smoothen_err2.png ' ')

### Sample12
![](./itr_results/iter_comp512/drawing.png ' ')

![](./itr_results/iter_comp512/new_smoothen_err2.png ' ')

### Sample13
![](./itr_results/iter_comp513/drawing.png ' ')

![](./itr_results/iter_comp513/new_smoothen_err2.png ' ')

### Sample14
![](./itr_results/iter_comp514/drawing.png ' ')

![](./itr_results/iter_comp514/new_smoothen_err2.png ' ')
