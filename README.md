# Mixer
reverseAllWords(sentence) {   let words = sentence.split(" ");     for (let i = 0; i &lt; words.length; i++) {       words[i] = reverseWord(words[i]);     }    return words.join(" "); },
