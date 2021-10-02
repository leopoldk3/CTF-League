October 1, 2021

1 - Open the link of the challenge.
2 - Inspect Element and use the select element button to click on the submit button. 
3 - Search the check_password() function with the find tool to get more info about the function. 
4 - find
    if (hash == "b0fef621727ff82a7d334d9f1f047dc662ed0e27e05aa8fd1aefd19b0fff312c") {
          document.getElementById("login").submit();
        }
5 - Take the Crack station link from the main page and input the above hash into the website. Get returned "pineapple"
6 - Input "pineapple" to the password input area on the main page. 
7 - again in inspect element click script and find the following function:
    function print_flag() {
        p="ABCDEFGHIJKLMNOPQRSTUVWXYZ";a="bfh{c1a34ccy3_u45u_Oe0jA5_4e3_t00Q}";b=p[s="substr"](13)+p[s](0,13);p+=p[l="toLowerCase"]();b+=b[l]();o='';for(i=0;a[i];i++)o+=b[p.indexOf(a[i])]||a[i];document.getElementById("bouncyLink").innerHTML = o;
      }
8 - take the "bfh{c1a34ccy3_u45u_Oe0jA5_4e3_t00Q}" and on cyberchef with the ROT13 decrypter
9 - the flag is given osu{p1n34ppl3_h45h_Br0wN5_4r3_g00D}

