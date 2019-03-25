# Generalized-Intersection-over-Union
Unofficial Implementation of Generalized Intersection over Union

## USAGE
```
def bbox_overlaps_giou(bboxes1, bboxes2):
    """Calculate the gious between each bbox of bboxes1 and bboxes2.

    Args:
        bboxes1(ndarray): shape (n, 4)
        bboxes2(ndarray): shape (k, 4)

    Returns:
        gious(ndarray): shape (n, k)
    """
```
