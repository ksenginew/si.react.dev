---
title: ස්ථාපන
---

<Intro>

React ආරම්භයේ සිට ක්‍රමයෙන් අනුගත වීම සඳහා නිර්මාණය කර ඇත. ඔබට අවශ්‍ය ආකාරයට React ටිකක් හෝ ගොඩක් භාවිතා කළ හැක. ඔබට React වල රසයක් ලබා ගැනීමට, HTML පිටුවකට යම් අන්තර්ක්‍රියාකාරීත්වයක් එක් කිරීමට හෝ සංකීර්ණ React බලැති යෙදුමක් ආරම්භ කිරීමට අවශ්‍ය වුවද, මෙම කොටස ඔබට ආරම්භ කිරීමට උදවු වනු ඇත.

</Intro>

<YouWillLearn isChapter={true}>

* [නව React ව්‍යාපෘතියක් ආරම්භ කරන්නේ කෙසේද](/learn/start-a-new-react-project)
* [පවතින ව්‍යාපෘතියකට React එකතු කරන්නේ කෙසේද](/learn/add-react-to-an-existing-project)
* [ඔබේ සංස්කාරකය සකසන්නේ කෙසේද](/learn/editor-setup)
* [React සංවර්ධක මෙවලම් ස්ථාපනය කරන්නේ කෙසේද](/learn/react-developer-tools)

</YouWillLearn>

## React උත්සාහ කරන්න {/*try-react*/}

React සමඟ සෙල්ලම් කිරීමට ඔබට කිසිවක් ස්ථාපනය කිරීමට අවශ්‍ය නැත. මෙම sandbox සංස්කරණය කිරීමට උත්සාහ කරන්න!

<Sandpack>

```js
function Greeting({ name }) {
  return <h1>Hello, {name}</h1>;
}

export default function App() {
  return <Greeting name="world" />
}
```

</Sandpack>

ඔබට එය කෙලින්ම සංස්කරණය කිරීමට හෝ ඉහළ දකුණු කෙළවරේ ඇති "ෆෝක්" බොත්තම එබීමෙන් නව ටැබ් එකකින් විවෘත කිරීමට හැකිය.

මෙම ලේඛනයේ බොහෝ පිටු වල මෙවැනි වැලි පෙට්ටි අඩංගු වේ. React ලේඛනයෙන් පිටත, React සඳහා සහය දක්වන බොහෝ online sandboxes තිබේ: උදාහරණයක් ලෙස,[CodeSandbox](https://codesandbox.io/s/new),[StackBlitz](https://stackblitz.com/fork/react), හෝ[CodePen.](https://codepen.io/pen?&editors=0010&layout=left&prefill_data_id=3f4569d1-1b11-4bce-bd46-89090eed5ddb)

### දේශීයව React උත්සාහ කරන්න {/*try-react-locally*/}

ඔබේ පරිගණකයේ දේශීයව React උත්සාහ කිරීමට,[මෙම HTML පිටුව බාගන්න.](https://gist.githubusercontent.com/gaearon/0275b1e1518599bbeafcde4722e79ed1/raw/db72dcbf3384ee1708c4a07d3be79860db04bff0/example.html) එය ඔබගේ සංස්කාරකයේ සහ ඔබගේ බ්‍රවුසරයේ විවෘත කරන්න!

## නව React ව්‍යාපෘතියක් ආරම්භ කරන්න {/*start-a-new-react-project*/}

ඔබට React සමඟ සම්පුර්ණයෙන්ම යෙදුමක් හෝ වෙබ් අඩවියක් තැනීමට අවශ්‍ය නම්,[නව React ව්‍යාපෘතියක් ආරම්භ කරන්න.](/learn/start-a-new-react-project)

## පවතින ව්‍යාපෘතියකට React එක් කරන්න {/*add-react-to-an-existing-project*/}

ඔබගේ පවතින යෙදුමේ හෝ වෙබ් අඩවියක React භාවිතා කිරීමට උත්සාහ කිරීමට අවශ්‍ය නම්,[පවතින ව්‍යාපෘතියකට React එක් කරන්න.](/learn/add-react-to-an-existing-project)

## මීළඟ පියවර {/*next-steps*/}

ඔබට දිනපතා හමුවන වැදගත්ම React සංකල්ප පිළිබඳ සංචාරයක් සඳහා [ඉක්මන් ආරම්භය](/learn) මාර්ගෝපදේශය වෙත යන්න.
