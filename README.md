## Dataset

[Dataset](https://drive.google.com/drive/u/2/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)

## ResNet (FC only after changing last layer)

**Training Loss**

`train Loss: 0.4110 Acc: 82.1083`

**Validation Loss**

`validation Loss: 0.3456 Acc: 85.9333`

**Confusion Matrix and Accuracy**

`train Confusion Matrix = tensor([[3671., 1248.],[ 454., 6627.]]) Accuracy of the network on 12000 train images: 85.81666666666666`

`validation Confusion Matrix = tensor([[479., 136.], [ 75., 810.]]) Accuracy of the network on 1500 validation images: 85.93333333333334`

`test Confusion Matrix = tensor([[535.,  80.], [ 52., 833.]]) Accuracy of the network on 1500 test images: 91.2`

## VGG (FC only after changing the last layer)

**Training Loss**

`train Loss: 0.2408 Acc: 90.5917`

**Validation Loss**

`validation Loss: 0.1983 Acc: 92.6000`

**Confusion Matrix and Accuracy**

`train Confusion Matrix = tensor([[4387.,  532.], [ 420., 6661.]]) Accuracy of the network on 12000 train images: 92.06666666666666`

`validation Confusion Matrix = tensor([[550.,  65.], [ 46., 839.]]) Accuracy of the network on 1500 validation images: 92.6`

`test Confusion Matrix = tensor([[585.,  30.], [  5., 880.]]) Accuracy of the network on 1500 test images: 97.66666666666667`

## ResNet (FC only)

**Training Loss**

`train Loss: 0.4425 Acc: 80.4083`

**Validation Loss**

`validation Loss: 0.3664 Acc: 85.9333`

**Confusion Matrix and Accuracy**

`train Confusion Matrix = tensor([[3695., 1224.], [ 542., 6539.]])Accuracy of the network on 12000 train images: 85.28333333333333`

`validation Confusion Matrix = tensor([[503., 112.], [ 99., 786.]]) Accuracy of the network on 1500 validation images: 85.93333333333334`

`test Confusion Matrix = tensor([[547.,  68.], [ 81., 804.]]) Accuracy of the network on 1500 test images: 90.06666666666666`

## ResNet (Training only on last 4 layers)

**Training Loss**

`train Loss: 0.1947 Acc: 92.6833`

**Validation Loss**

`validation Loss: 0.2079 Acc: 92.0667`

**Confusion Matrix and Accuracy**

`train Confusion Matrix = tensor([[4312.,  607.], [ 251., 6830.]]) Accuracy of the network on 12000 train images: 92.85`

`validation Confusion Matrix = tensor([[536.,  79.], [ 40., 845.]])  Accuracy of the network on 1500 validation images: 92.06666666666666`

`test Confusion Matrix = tensor([[575.,  40.], [ 10., 875.]]) Accuracy of the network on 1500 test images: 96.66666666666667`

## ResNet (Training the entire network)

**Training Loss**

`train Loss: 0.2089 Acc: 92.0667`

**Validation Loss**

`validation Loss: 0.1934 Acc: 92.6000`

**Confusion Matrix and Accuracy**

`train Confusion Matrix = tensor([[4282.,  637.], [ 213., 6868.]]) Accuracy of the network on 12000 train images: 92.91666666666667`

`validation Confusion Matrix = tensor([[555.,  60.], [ 51., 834.]]) Accuracy of the network on 1500 validation images: 92.6`

`test Confusion Matrix = tensor([[582.,  33.], [ 13., 872.]]) Accuracy of the network on 1500 test images: 96.93333333333334`

