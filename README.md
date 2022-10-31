# js-array-some-every
Exercises: .some .every

Had some trouble with hasNoDuplicates(arr)

function <b>hasNoDuplicates</b> (arr) {<br>
  return arr.every(function (value) {<br>
    return arr.indexOf(value) === arr.lastIndexOf(value);<br>
  });
}
<p><i>The part I struggled with was the .lastIndexOf(value) method. My first attempt was to use a loop in addition to the .every loop. Couldn't figure out how to compare one value to every other value in the same way as the answer did. 
