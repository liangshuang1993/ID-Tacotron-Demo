---
layout: default
---


# Audio samples of "Unsupervised Learning For Multi-style Speech Synthesis With Small Dataset"

<!-- ## Authors

Shuang Liang
Chenfeng Miao
Minchuan Chen
Jun Ma
Shaojun Wang
Jing Xiao

<font size=2>\**Equal contribution.*</font> -->

## Abstract

In this paper, we propose an unsupervised method for multi-style speech synthesis with small dataset. We extract style information by using a style encoder in addition to a common sequence-to-sequence text-to-speech model. Specifically, we conduct an instance discriminator to guide our style encoder to learn meaningful style representations from a variety of speech data in an unsupervised manner, which can significantly improve the expressiveness ability of the speech synthesis model. Furthermore, by introducing an information bottleneck layer to the style encoder, irrelevant information can be prevented from flowing into the model, therefore speech quality and style similarity can be improved. Our method still generates desirable speech using a small dataset where the baseline model fails to distinguish different styles. To demonstrate the performance of the proposed method, qualitative experiments are conducted, and the results indicate that our proposed method performs much better than the baseline model, with an ABX test score 0.857 versus 0 in emotional speech synthesis task and 0.525 versus 0.246 in multi-speaker speech synthesis task.



### Emotional Dataset

<table border="0">
<thead>
<tr>
<th style="text-align: center">Reference Aduio (Neutral)</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/1601.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<table border="0" >
<thead>
<tr>
<th style="text-align: center">With VIB</th>
<th style="text-align: center">Without VIB</th>
<th style="text-align: center">GST-Tacotron</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/ib/mel-1-1601.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/noib/mel-1-1601.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/gst/mel-1-1601.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

&nbsp; 

<table border="0">
<thead>
<tr>
<th style="text-align: center">Reference Aduio (Happy)</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/005.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<table border="0" >
<thead>
<tr>
<th style="text-align: center">With VIB</th>
<th style="text-align: center">Without VIB</th>
<th style="text-align: center">GST-Tacotron</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/ib/mel-1-005.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/noib/mel-1-005.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/gst/mel-1-005.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

&nbsp; 

<table border="0">
<thead>
<tr>
<th style="text-align: center">Reference Aduio (Sad)</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/2401.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<table border="0" >
<thead>
<tr>
<th style="text-align: center">With VIB</th>
<th style="text-align: center">Without VIB</th>
<th style="text-align: center">GST-Tacotron</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/ib/mel-1-2401.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/noib/mel-1-2401.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/gst/mel-1-2401.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

&nbsp; 

<table border="0">
<thead>
<tr>
<th style="text-align: center">Reference Aduio (Angry)</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/0171.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<table border="0" >
<thead>
<tr>
<th style="text-align: center">With VIB</th>
<th style="text-align: center">Without VIB</th>
<th style="text-align: center">GST-Tacotron</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/ib/mel-1-0171.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/noib/mel-1-0171.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/emotion/gst/mel-1-0171.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

&nbsp; 
&nbsp; 


### VCTK


<table border="0">
<thead>
<tr>
<th style="text-align: center">Reference Aduio (Female)</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/vctk/p228_371.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<table border="0" >
<thead>
<tr>
<th style="text-align: center">ID-Tacotron</th>
<th style="text-align: center">GST-Tacotron</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/vctk/id/mel-1-228.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/vctk/gst/mel-1-228.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

&nbsp; 

<table border="0">
<thead>
<tr>
<th style="text-align: center">Reference Aduio (Male)</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/vctk/p226_355.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<table border="0" >
<thead>
<tr>
<th style="text-align: center">ID-Tacotron</th>
<th style="text-align: center">GST-Tacotron</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center"><audio controls="controls"><source src="wavs/vctk/id/mel-1-226.wav" autoplay="">Your browser does not support the audio element.</audio></td>
<td style="text-align: center"><audio controls="controls"><source src="wavs/vctk/gst/mel-1-226.wav" autoplay="">Your browser does not support the audio element.</audio></td>
</tr>
</tbody>
</table>

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->
