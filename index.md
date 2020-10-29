---
layout: default
---


# Audio samples of "UNSUPERVISED LEARNING FOR MULTI-STYLE SPEECH SYNTHESIS WITH LIMITED DATA"

<!-- ## Authors

Shuang Liang
Chenfeng Miao
Minchuan Chen
Jun Ma
Shaojun Wang
Jing Xiao

<font size=2>\**Equal contribution.*</font> -->

## Abstract

Existing multi-style speech synthesis methods require either style labels or large amounts of unlabeled training data, making data acquisition difficult. In this paper, we present an unsupervised multi-style speech synthesis method that can be trained with limited data. We leverage instance discriminator to guide a style encoder to learn meaningful style representations from a multi-style dataset. Furthermore, we employ information bottleneck to filter out style-irrelevant information in the representations, which can improve speech quality and style similarity. Our method is able to produce desirable speech using a fairly small dataset, where the baseline {GST-Tacotron} fails. ABX tests show that our model significantly outperforms {GST-Tacotron} in both emotional speech synthesis task and multi-speaker speech synthesis task. In addition, we demonstrate that our method is able to learn meaningful style features with only 50 training samples per style.


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
