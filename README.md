# 💫𝙺𝙸𝙽𝙶_𝙲𝙷𝙰𝙼𝙸ᵀᴹ-𝙼𝙳💫
#### TOTAL REPO VIEWS📍
![Visitor Count](https://profile-counter.glitch.me/terror-boy/count.svg)

    💫𝙺𝙸𝙽𝙶_𝙲𝙷𝙰𝙼𝙸ᵀᴹ-𝙼𝙳💫 V3...


   
   
   
   
   ```Thanks Fro using 💫𝙺𝙸𝙽𝙶_𝙲𝙷𝙰𝙼𝙸ᵀᴹ-𝙼𝙳💫```


# Support Group <a href="watsapp group link"><img alt="WhatsApp" src="https://img.shields.io/badge/-Whatsapp%20Group-lightgrey?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>


 </a>

</p>

<div align="center">

  <p align="center">

<img src="https://i.ibb.co/K0nmnF3/chami.png" alt="GIF" width="300" height="270"/>

</p>

  <p align="center">

<a href="#"><img title="CHAMIMD" src="https://img.shields.io/badge/King-chami-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>

</p>

</div>

<p align="center">By KING CHAMI>| © | Reserved  </br> 
 

***ඉස්සෙල්ලාම ඔයාලා FORK කරගෙන ඉන්න***

[FORK](https://github.com/KINGCHAMIYA00/KING-CHAMI-V1/fork)

***ඊට පස්සේ QR CODE එක ගන්න.ඒකට පල්ලෙ තියෙන බටන් එක ඔබන්න***

[![Run on Repl.it](https://repl.it/badge/github/quiec/whatsasena)](https://replit.com/@kingchamiya/-?v=1)

***ඊට පස්සේ විඩියෝ එකේ තියෙන විදිහට ඇප් එක හදලා ඉවර වෙලා පල්ලෙ තියෙන බටන් එක ඔබන්න***

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


## Owner:
* [`KING-CHAMI`](https://github.com/KINGCHAMIYA00)

## Thanks To






























function getCountImage(count) {
  // This is not the greatest way for generating an SVG but it'll do for now
  const countArray = count.toString().padStart(PLACES, '0').split('');

  const parts = countArray.reduce((acc, next, index) => `
        ${acc}
        <rect id="Rectangle" fill="#000000" x="${index * 32}" y="0.5" width="29" height="29"></rect>
        <text id="0" font-family="Courier" font-size="24" font-weight="normal" fill="#00FF13">
            <tspan x="${index * 32 + 7}" y="22">${next}</tspan>
        </text>
`, '');
  
  return `<?xml version="1.0" encoding="UTF-8"?>
<svg width="${PLACES * 32}px" height="30px" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <title>Count</title>
    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
      ${parts}
    </g>
</svg>
}
