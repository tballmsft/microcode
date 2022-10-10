---
image: ./docs/images/generated/sample_double_counter.png
---

# Double Counter

![double counter program](../images/generated/sample_double_counter.png){:class="sample"}

This program counts how many times you press `button A` or `button B`.

-   [Open in MicroCode](/microcode/#H4sIANizQWMAA6VRy27CMBD8pQBNqxxxFIW1cKJgQx63QopwakqlgGLz9XXsVBAjTpxWs5qdndn9UrjbHYOfKt4cofn9ADHnqTjrCkMlurZ8fY14QTueUXjPFUaE43oZ4kTPbOHbk2l+OOwWyAcxCZYLzVeGxwg1PGR5kSThaE6RSOsWXqt9MNMTRIHwWs01ezMmkMWlwauGGB/M+khIgxBwjVnp6vjZy7tt5hU3u+LEmbdZz8GgQfv+nZYca8HYNxOnKpftVuF6T+XzO7O5mzd8uLH9xX9OP7M4trj0rA/P6DMGXcahx1NXJ11bjy/sHjI/+ZX+R591vxk0+rvOnPvNJjdOiKdVga+feXCB5sTrBi6Ev8mE4uAPhFD/6bgCAAA=)

Page 1 is used to track `A` and page `2` for `B`. This is a more advanced version of the [counter sample](./counter).

## ![page 1](../images/generated/icon_M1.png){:class="icon"} page 1

![double counter page 1 program](../images/generated/sample_double_counter_page_1.png){:class="sample"}

This page implements a counter using variable `X`
and ![button A](../images/generated/icon_F3.png){:class="icon"} button `A`. When ![button B](../images/generated/icon_F4.png){:class="icon"} button `B` is pressed, we switch to ![page 2](../images/generated/icon_M2.png){:class="icon"} page 2.

![when button A pressed, increment X](../images/generated/sample_double_counter_page_1_rule_3.png){:class="rule"}

-   **when** ![press](../images/generated/icon_S2.png){:class="icon"} press ![button A](../images/generated/icon_F3.png){:class="icon"} button A, **do** ![set variable X](../images/generated/icon_A9A.png){:class="icon"} set variable `X` to ![get variable X](../images/generated/icon_M20A.png){:class="icon"} variable `X` plus ![value 1](../images/generated/icon_M6.png){:class="icon"} `value 1`

![when press button A, increment variable X](../images/generated/sample_double_counter_page_1_rule_4.png){:class="rule"}

-   **when** ![variable X changed](../images/generated/icon_S9A.png){:class="icon"} variable X changed, **do** show variable `X` value.

## ![page 2](../images/generated/icon_M2.png){:class="icon"} page 2

![double counter page 2 program](../images/generated/sample_double_counter_page_2.png){:class="sample"}