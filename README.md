# frequencyDictionaryOfGoDocs

1 was made to extract htmls from go docs for making a frequency dictionary
****
then I used replacing in Sublime Text to clean unnecessary symbols with regexp:\n
  (<p>)([\\\sa-zA-Z0-9(),.;&':\-<>/#!?+`=]*)(</p>) - this expression found text between tags <p> and </p>
  then I replaced the tags by symbols ~ and № because this symbols wasn't in htmls before,
  after that I can delete all unusable text out of the text
I did it by regexp (№)([\\\sa-zA-Z0-9(),.;&':\-<>/#!?+`="▾*\[\]{}_—▹%|İKᾭ@世界$\^]*)(~) 
