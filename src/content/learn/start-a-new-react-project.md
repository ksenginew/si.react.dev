---
title: නව React ව්‍යාපෘතියක් ආරම්භ කරන්න
---

<Intro>

ඔබට React සමඟ සම්පුර්ණයෙන්ම නව යෙදුමක් හෝ නව වෙබ් අඩවියක් තැනීමට අවශ්‍ය නම්, ප්‍රජාව තුළ ජනප්‍රිය React බලැති frameworks වලින් එකක් තෝරා ගැනීම අපි නිර්දේශ කරමු. Frameworks මඟින් routing, දත්ත ලබා ගැනීම (data fetching) සහ HTML ජනනය කිරීම ඇතුළුව බොහෝ apps සහ අඩවිවලට අවසානයේ අවශ්‍ය වන විශේෂාංග සපයයි.

</Intro>

<Note>

**දේශීය සංවර්ධනය සඳහා ඔබ [Node.js](https://nodejs.org/en/) ස්ථාපනය කිරීමට අවශ්යයි.** *තවද* ඔයාට පුළුවන් නිෂ්පාදනයේදී Node.js භාවිතා කිරීමට තෝරන්න, නමුත් ඔබ එසේ කිරීමට අවශ්‍ය නැත. බොහෝ React framworks ස්ථිතික (static) HTML/CSS/JS ෆෝල්ඩරයකට අපනයනය (export) කිරීමට සහාය වේ.

</Note>

## නිෂ්පාදන ශ්‍රේණියේ React frameworks {/*production-grade-react-frameworks*/}

### Next.js {/_nextjs_/}

**[Next.js](https://nextjs.org/) සම්පූර්ණ React frameworksවකි.** එය බහුකාර්ය වන අතර ඔබට ඕනෑම ප්‍රමාණයක React apps නිර්මාණය කිරීමට ඉඩ සලසයි - බොහෝ දුරට ස්ථිතික (static) බ්ලොග් එකක සිට සංකීර්ණ ගතික (dynamic) යෙදුමක් දක්වා. නව Next.js ව්‍යාපෘතියක් තැනීමට, ඔබේ ටර්මිනලය තුළ ධාවනය කරන්න:

<TerminalBlock>
npx create-next-app
</TerminalBlock>

ඔබ Next.js වෙත අලුත් නම්, [Next.js නිබන්ධනය](https://nextjs.org/learn/foundations/about-nextjs) පරීක්ෂා කරන්න.

Next.js [Vercel](https://vercel.com/) විසින් නඩත්තු කරනු ලැබේ. ඔයාට පුළුවන් ඕනෑම Node.js හෝ serverless hosting වෙත, හෝ ඔබගේම සේවාදායකය වෙත [Next.js යෙදුමක් යොදවන්න](https://nextjs.org/docs/deployment).[සම්පුර්ණයෙන්ම ස්ථිතික Next.js apps](https://nextjs.org/docs/advanced-features/static-html-export) ඕනෑම ස්ථිතික සත්කාරකයකට (static hosting) යෙදවිය හැක.

### Remix {/_*remix*_/}

**[Remix](https://remix.run/)යනු nested routing සහිත full-stack React frameworksවකි.** එය ඔබගේ යෙදුම සමාන්තරව දත්ත පූරණය කළ හැකි සහ පරිශීලක ක්‍රියාවන්ට ප්‍රතිචාර වශයෙන් නැවුම් කළ හැකි කැදැලි කොටස් (nested parts) වලට කැඩීමට ඔබට ඉඩ සලසයි. නව Remix ව්‍යාපෘතියක් තැනීමට, ධාවනය කරන්න:

<TerminalBlock>
npx create-remix
</TerminalBlock>

ඔබ Remix වෙත අලුත් නම්, Remix පරීක්ෂා කරන්න[බ්ලොග් නිබන්ධනය](https://remix.run/docs/en/main/tutorials/blog)(කෙටි) සහ[apps නිබන්ධනය](https://remix.run/docs/en/main/tutorials/jokes)(දිගු).

Remix [Shopify](https://www.shopify.com/) විසින් නඩත්තු කරනු ලැබේ. ඔබ Remix ව්‍යාපෘතියක් සාදන විට, [ඔබගේ යෙදවීමේ ඉලක්කය තෝරන්න](https://remix.run/docs/en/main/guides/deployment) ඔබට අවශ්‍ය වේ. ඔබට Remix යෙදුමක් [ඇඩප්ටරයක්](https://remix.run/docs/en/main/other-api/adapter) භාවිතා කිරීමෙන් හෝ ලිවීමෙන් ඕනෑම Node.js හෝ serverless hosting වෙත යෙදිය හැක.

### Gatsby {/*gatsby*/}

**[Gatsby](https://www.gatsbyjs.com/) වේගවත් CMS පිටුබලය සහිත වෙබ් අඩවි සඳහා React frameworksවකි.**එහි පොහොසත් plugin පරිසර පද්ධතිය සහ එහි GraphQL දත්ත ස්ථරය එක් වෙබ් අඩවියකට අන්තර්ගතය, API සහ සේවාවන් ඒකාබද්ධ කිරීම සරල කරයි. නව Gatsby ව්‍යාපෘතියක් නිර්මාණය කිරීමට, ධාවනය කරන්න:

<TerminalBlock>
npx create-gatsby
</TerminalBlock>

ඔබ Gatsby වෙත අලුත් නම්, [Gatsby නිබන්ධනය](https://www.gatsbyjs.com/docs/tutorial/) පරීක්ෂා කරන්න.

ගැට්ස්බි [නෙට්ලිෆයි](https://www.netlify.com/) විසින් නඩත්තු කරනු ලැබේ. ඔයාට ඕනෑම ස්ථිතික සත්කාරකයකට [සම්පුර්ණ ස්ථිතික Gatsby අඩවියක් යෙදවීමට](https://www.gatsbyjs.com/docs/how-to/previews-deploys-hosting) පුළුවන්. ඔබ server-only විශේෂාංග භාවිතා කිරීමට තෝරා ගන්නේ නම්, ඔබගේ hosting provider Gatsby සඳහා ඔවුන්ට සහය දක්වන බවට වග බලා ගන්න.

### Expo (for native apps) {/*expo*/}

**[Expo](https://expo.dev/) සැබෑ දේශීය UI සමඟ විශ්වීය Android, iOS සහ web apps නිර්මාණය කිරීමට ඔබට ඉඩ සලසන React Framework වේ.** එය [React Native](https://reactnative.dev/) සඳහා SDK සපයයි. එය දේශීය කොටස් භාවිතා කිරීමට පහසු කරයි. නව Expo ව්‍යාපෘතියක් නිර්මාණය කිරීමට, ධාවනය කරන්න:

<TerminalBlock>
npx create-expo-app
</TerminalBlock>

ඔබ Expo සඳහා අලුත් නම්, [Expo නිබන්ධනය](https://docs.expo.dev/tutorial/introduction/) පරීක්ෂා කරන්න.

එක්ස්පෝ නඩත්තු කරන්නේ[එක්ස්පෝ (සමාගම)](https://expo.dev/about). Expo සමඟින් apps තැනීම නොමිලේ, ඔබට ඒවා Google සහ Apple apps වෙළඳසැල් වෙත සීමාවකින් තොරව ඉදිරිපත් කළ හැක. Expo අතිරේකව තෝරා ගැනීමේ ගෙවුම් වලාකුළු සේවා (cloud services) සපයයි.

<DeepDive>

#### frameworksවක් නොමැතිව මට React භාවිතා කළ හැකිද? Can I use React without a framework? {/*can-i-use-react-without-a-framework*/}

ඔබට frameworksවක් නොමැතිව අනිවාර්යයෙන්ම React භාවිතා කළ හැක--ඔබ කැමති ආකාරයට [ඔබේ පිටුවේ කොටසක් සඳහා React භාවිතා කරන්න.](/learn/add-react-to-an-existing-project#using-react-for-a-part-of-your-existing-page) **කෙසේ වෙතත්, ඔබ නව යෙදුමක් හෝ සම්පූර්ණයෙන්ම React සමඟින් අඩවියක් ගොඩනඟන්නේ නම්, අපි frameworksවක් භාවිතා කිරීම නිර්දේශ කරමු.**

මෙන්න හේතුව.

ඔබට මුලදී routing හෝ දත්ත ලබා ගැනීම අවශ්‍ය නැතත්, ඔබට ඒවා සඳහා පුස්තකාල කිහිපයක් එක් කිරීමට අවශ්‍ය වනු ඇත. ඔබගේ ජාවාස්ක්‍රිප්ට් බණ්ඩලය සෑම නව විශේෂාංගයක් සමඟම වර්ධනය වන විට, ඔබට සෑම මාර්ගයකටම කේත වෙන් කරන්නේ කෙසේදැයි සොයා ගැනීමට සිදු විය හැක. ඔබගේ දත්ත ලබා ගැනීමේ අවශ්‍යතා වඩාත් සංකීර්ණ වන බැවින්, ඔබගේ යෙදුම ඉතා මන්දගාමී බවක් දැනෙන server-client ජාල දිය ඇලි (network waterfalls) ඔබට හමුවීමට ඉඩ ඇත. ඔබේ ප්‍රේක්ෂකයන්ට දුර්වල ජාල තත්ත්වයන් සහ අඩු-අන්ත (low-end) උපාංග සහිත පරිශීලකයින් වැඩි සංඛ්‍යාවක් ඇතුළත් වන බැවින්, සේවාදායකයේ හෝ ගොඩනඟන කාලය තුළ කලින් අන්තර්ගතය සංදර්ශන කිරීමට ඔබට ඔබේ සංරචකවලින් HTML ජනනය කිරීමට අවශ්‍ය විය හැකිය. සේවාදායකයේ හෝ ගොඩ නැගීමේදී ඔබගේ සමහර කේතයන් ධාවනය කිරීමට ඔබගේ සැකසුම වෙනස් කිරීම ඉතා උපක්‍රමශීලී විය හැක.

**මෙම ගැටළු React-විශේෂිත නොවේ. Svelte සතුව SvelteKit, Vue සතුව Nuxt සහ යනාදිය ඇත්තේ මේ නිසාය.**මෙම ගැටලු ඔබ විසින්ම විසඳා ගැනීමට, ඔබ ඔබේ router සමඟ සහ ඔබේ දත්ත ලබා ගැනීමේ පුස්තකාලය සමඟ ඔබේ බණ්ඩලය ඒකාබද්ධ කිරීමට අවශ්‍ය වනු ඇත. මූලික සැකසුම ක්‍රියාත්මක කිරීම අපහසු නැත, නමුත් කාලයත් සමඟ වැඩෙන විට පවා ඉක්මනින් පූරණය වන යෙදුමක් සෑදීමේදී සියුම්කම් රාශියක් ඇතුළත් වේ. ඔබට අවම apps කේත ප්‍රමාණයක් යැවීමට අවශ්‍ය වනු ඇත, නමුත් පිටුව සඳහා අවශ්‍ය ඕනෑම දත්තයකට සමාන්තරව තනි server-client වට සංචාරයක් තුළ එය කරන්න. ප්‍රගතිශීලී වැඩිදියුණු කිරීම් සඳහා සහය දැක්වීම සඳහා ඔබේ JavaScript කේතය ක්‍රියාත්මක වීමට පෙර පිටුව අන්තර්ක්‍රියාකාරී වීමට ඔබට අවශ්‍ය වනු ඇත. ඔබට ඕනෑම තැනක සත්කාරකත්වය දැක්විය හැකි සහ තවමත් JavaScript අබල කර ඇති ඔබේ අලෙවිකරණ පිටු සඳහා සම්පූර්ණ ස්ථිතික HTML ගොනු ෆෝල්ඩරයක් ජනනය කිරීමට අවශ්‍ය විය හැක. මෙම හැකියාවන් ඔබම ගොඩනඟා ගැනීම සැබෑ කාර්යයක් වේ.

**මෙම පිටුවේ ඇති React frameworks ඔබේ පැත්තෙන් අමතර වැඩක් නොමැතිව පෙරනිමියෙන් මෙවැනි ගැටලු විසඳයි.**ඔවුන් ඔබට ඉතා සිහින්ව ආරම්භ කිරීමට සහ ඔබේ අවශ්‍යතා සමඟ ඔබේ යෙදුම පරිමාණය කිරීමට ඉඩ දෙයි. සෑම React frameworksවකටම ප්‍රජාවක් ඇත, එබැවින් ප්‍රශ්නවලට පිළිතුරු සෙවීම සහ මෙවලම් උත්ශ්‍රේණි කිරීම පහසුය. විවිධ ව්‍යාපෘති අතර සන්දර්භය සහ කුසලතා රඳවා තබා ගැනීමට ඔබට සහ අනෙක් අයට උදවු කරමින්, frameworks ඔබේ කේතයට ව්‍යුහයක් ද ලබා දෙයි. අනෙක් අතට, අභිරුචි සැකසුමකින් සහය නොදක්වන පරායත්ත (dependancies) අනුවාදවල සිරවීම පහසු වන අතර, ප්‍රජාවක් හෝ උත්ශ්‍රේණිගත කිරීමේ මාර්ගයක් නොමැති එකක් වුවද (සහ එය අප විසින් සාදන ලද ඒවා වැනි දෙයක් නම්, ඔබ අත්‍යවශ්‍යයෙන්ම ඔබේම framework නිර්මාණය කරයි. අතීතය, වඩාත් අහඹු ලෙස නිර්මාණය කර ඇත).

ඔබට තවමත් ඒත්තු ගැන්වී නොමැති නම්, හෝ ඔබේ යෙදුමට මෙම frameworks මඟින් හොඳින් සේවය කර නොමැති අසාමාන්‍ය සීමාවන් තිබේ නම් සහ ඔබ ඔබේම අභිරුචි සැකසුම පෙරළීමට කැමති නම්, අපට ඔබව නැවැත්විය නොහැක--ඒ සඳහා යන්න! අල්ලා ගන්න`react`සහ`react-dom`npm වෙතින්, ඔබේ අභිරුචි ගොඩනැගීමේ ක්‍රියාවලිය වැනි බණ්ඩලයක් සමඟ සකසන්න[ඉක්මනින්](https://vitejs.dev/)හෝ[පාර්සලය](https://parceljs.org/), සහ මාර්ගගත කිරීම, ස්ථිතික උත්පාදනය හෝ සේවාදායක පැත්තේ විදැහුම්කරණය සහ තවත් දේ සඳහා ඔබට අවශ්‍ය පරිදි වෙනත් මෙවලම් එක් කරන්න.</DeepDive>

## Bleeding-edge React frameworks {/*bleeding-edge-react-frameworks*/}

React වැඩිදියුණු කිරීම දිගටම කරගෙන යන්නේ කෙසේදැයි අපි ගවේෂණය කර ඇති පරිදි, React පරිශීලකයින්ට වඩා හොඳ apps තැනීමට උදවු කිරීමට අපට ඇති ලොකුම අවස්ථාව frameworks සමඟ (විශේෂයෙන්, මාර්ගගත කිරීම, බද්ධ කිරීම සහ සේවාදායක තාක්ෂණයන් සමඟ) React වඩාත් සමීපව ඒකාබද්ධ කිරීම බව අපට වැටහුණි. Next.js කණ්ඩායම පර්යේෂණ, සංවර්ධනය, ඒකාබද්ධ කිරීම සහ frameworks-අඥෙයවාදී රුධිර වහනය-එජ් React විශේෂාංග පරීක්ෂා කිරීමේදී අප සමඟ සහයෝගයෙන් කටයුතු කිරීමට එකඟ වී ඇත.[React සේවාදායක සංරචක.](/blog/2023/03/22/react-labs-what-we-have-been-working-on-march-2023#react-server-components)

මෙම විශේෂාංග සෑම දිනකම නිෂ්පාදනයට සූදානම් වීමට සමීප වෙමින් පවතින අතර, අපි ඒවා ඒකාබද්ධ කිරීම පිළිබඳව අනෙකුත් bundler සහ frameworks සංවර්ධකයින් සමඟ සාකච්ඡා කරමින් සිටිමු. අපගේ බලාපොරොත්තුව වන්නේ වසරකින් හෝ දෙකකින්, මෙම පිටුවේ ලැයිස්තුගත කර ඇති සියලුම frameworks මෙම විශේෂාංග සඳහා පූර්ණ සහාය ලබා දෙනු ඇත. (ඔබ මෙම විශේෂාංග සමඟ අත්හදා බැලීමට අප සමඟ හවුල් වීමට කැමති frameworks කතුවරයෙක් නම්, කරුණාකර අපට දන්වන්න!)

### Next.js (apps router) {/*nextjs-app-router*/}

**[Next.js apps router](https://beta.nextjs.org/docs/getting-started) React කණ්ඩායමේ පූර්ණ-අට්ටි ගෘහ නිර්මාණ දැක්ම සපුරාලීම අරමුණු කරගත් Next.js API හි ප්‍රතිනිර්මාණයකි.** එය සේවාදායකයේ හෝ ගොඩනැගීමේදී පවා ක්‍රියාත්මක වන අසමමුහුර්ත සංරචකවල දත්ත ලබා ගැනීමට ඔබට ඉඩ සලසයි.

Next.js [Vercel](https://vercel.com/) විසින් නඩත්තු කරනු ලැබේ. ඔයාට පුළුවන්[Next.js යෙදුමක් යොදවන්න](https://nextjs.org/docs/deployment)ඕනෑම Node.js හෝ serverless hosting වෙත, හෝ ඔබගේම සේවාදායකය වෙත. Next.js ද සහය දක්වයි[ස්ථිතික අපනයනය](https://beta.nextjs.org/docs/configuring/static-export)සේවාදායකයක් අවශ්‍ය නොවන.<Pitfall>

Next.js App Router යනු**දැනට බීටා හි පවතින අතර නිෂ්පාදනය සඳහා තවමත් නිර්දේශ කර නොමැත**(මාර්තු 2023 වන විට). පවතින Next.js ව්‍යාපෘතියක එය අත්හදා බැලීමට,[මෙම වර්ධක සංක්‍රමණ මාර්ගෝපදේශය අනුගමනය කරන්න](https://beta.nextjs.org/docs/upgrade-guide#migrating-from-pages-to-app).

</Pitfall>

<DeepDive>

#### React කණ්ඩායමේ full-stack ගෘහ නිර්මාණ දැක්ම සෑදෙන විශේෂාංග මොනවාද? {/*which-features-make-up-the-react-teams-full-stack-architecture-vision*/}

Next.js හි apps රවුටර බණ්ඩලය නිලය සම්පූර්ණයෙන්ම ක්‍රියාත්මක කරයි[React සේවාදායක සංරචක පිරිවිතර](https://github.com/reactjs/rfcs/blob/main/text/0188-server-components.md). මෙය ඔබට තනි React ගසක ගොඩනැගීමට කාලය, සේවාදායකයට පමණක් සහ අන්තර්ක්‍රියාකාරී සංරචක මිශ්‍ර කිරීමට ඉඩ සලසයි.

උදාහරණයක් ලෙස, ඔබට සේවාදායකයට පමණක් React සංරචකයක් ලෙස ලිවිය හැක`async`දත්ත සමුදායකින් හෝ ගොනුවකින් කියවන කාර්යය. එවිට ඔබට එයින් ඔබේ අන්තර්ක්‍රියාකාරී සංරචක වෙත දත්ත යැවිය හැක:

```js
// This component runs *only* on the server (or during the build).
async function Talks({ confId }) {
  // 1. You're on the server, so you can talk to your data layer. API endpoint not required.
  const talks = await db.Talks.findAll({ confId });

  // 2. Add any amount of rendering logic. It won't make your JavaScript bundle larger.
  const videos = talks.map(talk => talk.video);

  // 3. Pass the data down to the components that will run in the browser.
  return <SearchableVideoList videos={videos} />;
}
```

Next.js apps router ද [Suspense සමඟ දත්ත ලබා ගැනීම](/blog/2022/03/29/react-v18#suspense-in-data-frameworks) සමඟ ඒකාබද්ධ වේ. ඔබගේ React වෘක්ෂය තුළ සෘජුවම ඔබගේ පරිශීලක අතුරුමුහුණතේ විවිධ කොටස් සඳහා පැටවීමේ තත්වයක් (skeleton placeholder වැනි) සඳහන් කිරීමට මෙය ඔබට ඉඩ සලසයි:

```js
<Suspense fallback={<TalksLoading />}>
  <Talks confId={conf.id} />
</Suspense>
```

Server Components සහ Suspense යනු Next.js විශේෂාංග වලට වඩා React විශේෂාංග වේ. කෙසේ වෙතත්, frameworks මට්ටමින් ඒවා සම්මත කිරීම සඳහා buy-in සහ සුළු නොවන ක්රියාත්මක කිරීමේ කාර්යයක් අවශ්ය වේ. මේ මොහොතේ, Next.js apps router වඩාත්ම සම්පූර්ණ ක්‍රියාත්මක කිරීම වේ. මෙම විශේෂාංග මීළඟ පරම්පරාවේ frameworks තුළ ක්‍රියාත්මක කිරීම පහසු කිරීමට React කණ්ඩායම bundler සංවර්ධකයින් සමඟ කටයුතු කරයි.

</DeepDive>