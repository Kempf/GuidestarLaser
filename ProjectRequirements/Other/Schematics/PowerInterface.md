%!PS-Adobe-3.0 EPSF-3.0
%%Creator: Mayura Draw, Version 4.5
%%Title: PowerInterface.md
%%CreationDate: Wed Apr 05 11:34:47 2017
%%BoundingBox: 20 27 591 784
%%DocumentFonts: ArialMT
%%Orientation: Landscape
%%EndComments
%%BeginProlog
%%BeginResource: procset MayuraDraw_ops
%%Version: 4.5
%%Copyright: (c) 1993-2003 Mayura Software
/PDXDict 100 dict def
PDXDict begin
% width height matrix proc key cache
% definepattern -\> font
/definepattern { %def
  7 dict begin
    /FontDict 9 dict def
    FontDict begin
      /cache exch def
      /key exch def
      /proc exch cvx def
      /mtx exch matrix invertmatrix def
      /height exch def
      /width exch def
      /ctm matrix currentmatrix def
      /ptm matrix identmatrix def
      /str
      (xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
      def
    end
    /FontBBox [ %def
      0 0 FontDict /width get
      FontDict /height get
    ] def
    /FontMatrix FontDict /mtx get def
    /Encoding StandardEncoding def
    /FontType 3 def
    /BuildChar { %def
      pop begin
      FontDict begin
        width 0 cache { %ifelse
          0 0 width height setcachedevice
        }{ %else
          setcharwidth
        } ifelse
        0 0 moveto width 0 lineto
        width height lineto 0 height lineto
        closepath clip newpath
        gsave proc grestore
      end end
    } def
    FontDict /key get currentdict definefont
  end
} bind def

% dict patternpath -
% dict matrix patternpath -
/patternpath { %def
  dup type /dicttype eq { %ifelse
    begin FontDict /ctm get setmatrix
  }{ %else
    exch begin FontDict /ctm get setmatrix
    concat
  } ifelse
  currentdict setfont
  FontDict begin
    FontMatrix concat
    width 0 dtransform
    round width div exch round width div exch
    0 height dtransform
    round height div exch
    round height div exch
    0 0 transform round exch round exch
    ptm astore setmatrix

    pathbbox
    height div ceiling height mul 4 1 roll
    width div ceiling width mul 4 1 roll
    height div floor height mul 4 1 roll
    width div floor width mul 4 1 roll

    2 index sub height div ceiling cvi exch
    3 index sub width div ceiling cvi exch
    4 2 roll moveto

    FontMatrix ptm invertmatrix pop
    { %repeat
      gsave
        ptm concat
        dup str length idiv { %repeat
          str show
        } repeat
        dup str length mod str exch
        0 exch getinterval show
      grestore
      0 height rmoveto
    } repeat
    pop
  end end
} bind def

% dict patternfill -
% dict matrix patternfill -
/patternfill { %def
  gsave
    eoclip patternpath
  grestore
  newpath
} bind def

/img { %def
  gsave
  /imgh exch def
  /imgw exch def
  concat
  imgw imgh 8
  [imgw 0 0 imgh neg 0 imgh]
  /colorstr 768 string def
  /colorimage where {
    pop
    { currentfile colorstr readhexstring pop }
    false 3 colorimage
  }{
    /graystr 256 string def
    {
      currentfile colorstr readhexstring pop
      length 3 idiv
      dup 1 sub 0 1 3 -1 roll
      {
        graystr exch
        colorstr 1 index 3 mul get 30 mul
        colorstr 2 index 3 mul 1 add get 59 mul
        colorstr 3 index 3 mul 2 add get 11 mul
        add add 100 idiv
        put
      } for
      graystr 0 3 -1 roll getinterval
    } image
  } ifelse
  grestore
} bind def

/arrowhead {
  gsave
    [] 0 setdash
    strokeC strokeM strokeY strokeK setcmykcolor
    2 copy moveto
    4 2 roll exch 4 -1 roll exch
    sub 3 1 roll sub
    exch atan rotate dup scale
    arrowtype
    dup 0 eq {
      -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 1 eq {
      0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 2 eq {
      -6 -6 rmoveto 6 6 rlineto -6 6 rlineto
      -1.4142 -1.4142 rlineto 4.5858 -4.5858 rlineto
      -4.5858 -4.5858 rlineto closepath fill
    } if
    dup 3 eq {
      -6 0 rmoveto -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 4 eq {
      -9 0 rmoveto 0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 5 eq {
      currentpoint newpath 3 0 360 arc
      closepath fill
    } if
    dup 6 eq {
      2.5 2.5 rmoveto 0 -5 rlineto -5 0 rlineto 0 5 rlineto
      closepath fill
    } if
    pop
  grestore
} bind def

/setcmykcolor where { %ifelse
  pop
}{ %else
  /setcmykcolor {
     /black exch def /yellow exch def
     /magenta exch def /cyan exch def
     cyan black add dup 1 gt { pop 1 } if 1 exch sub
     magenta black add dup 1 gt { pop 1 } if 1 exch sub
     yellow black add dup 1 gt { pop 1 } if 1 exch sub
     setrgbcolor
  } bind def
} ifelse

/RE { %def
  findfont begin
  currentdict dup length dict begin
    { %forall
      1 index /FID ne { def } { pop pop } ifelse
    } forall
    /FontName exch def dup length 0 ne { %if
      /Encoding Encoding 256 array copy def
      0 exch { %forall
        dup type /nametype eq { %ifelse
          Encoding 2 index 2 index put
          pop 1 add
        }{ %else
          exch pop
        } ifelse
      } forall
    } if pop
  currentdict dup end end
  /FontName get exch definefont pop
} bind def

/spacecount { %def
  0 exch
  ( ) { %loop
    search { %ifelse
      pop 3 -1 roll 1 add 3 1 roll
    }{ pop exit } ifelse
  } loop
} bind def

/WinAnsiEncoding [
  39/quotesingle 96/grave 130/quotesinglbase/florin/quotedblbase
  /ellipsis/dagger/daggerdbl/circumflex/perthousand
  /Scaron/guilsinglleft/OE 145/quoteleft/quoteright
  /quotedblleft/quotedblright/bullet/endash/emdash
  /tilde/trademark/scaron/guilsinglright/oe/dotlessi
  159/Ydieresis 164/currency 166/brokenbar 168/dieresis/copyright
  /ordfeminine 172/logicalnot 174/registered/macron/ring
  177/plusminus/twosuperior/threesuperior/acute/mu
  183/periodcentered/cedilla/onesuperior/ordmasculine
  188/onequarter/onehalf/threequarters 192/Agrave/Aacute
  /Acircumflex/Atilde/Adieresis/Aring/AE/Ccedilla
  /Egrave/Eacute/Ecircumflex/Edieresis/Igrave/Iacute
  /Icircumflex/Idieresis/Eth/Ntilde/Ograve/Oacute
  /Ocircumflex/Otilde/Odieresis/multiply/Oslash
  /Ugrave/Uacute/Ucircumflex/Udieresis/Yacute/Thorn
  /germandbls/agrave/aacute/acircumflex/atilde/adieresis
  /aring/ae/ccedilla/egrave/eacute/ecircumflex
  /edieresis/igrave/iacute/icircumflex/idieresis
  /eth/ntilde/ograve/oacute/ocircumflex/otilde
  /odieresis/divide/oslash/ugrave/uacute/ucircumflex
  /udieresis/yacute/thorn/ydieresis
] def

/SymbolEncoding [
  32/space/exclam/universal/numbersign/existential/percent
  /ampersand/suchthat/parenleft/parenright/asteriskmath/plus
  /comma/minus/period/slash/zero/one/two/three/four/five/six
  /seven/eight/nine/colon/semicolon/less/equal/greater/question
  /congruent/Alpha/Beta/Chi/Delta/Epsilon/Phi/Gamma/Eta/Iota
  /theta1/Kappa/Lambda/Mu/Nu/Omicron/Pi/Theta/Rho/Sigma/Tau
  /Upsilon/sigma1/Omega/Xi/Psi/Zeta/bracketleft/therefore
  /bracketright/perpendicular/underscore/radicalex/alpha
  /beta/chi/delta/epsilon/phi/gamma/eta/iota/phi1/kappa/lambda
  /mu/nu/omicron/pi/theta/rho/sigma/tau/upsilon/omega1/omega
  /xi/psi/zeta/braceleft/bar/braceright/similar
  161/Upsilon1/minute/lessequal/fraction/infinity/florin/club
  /diamond/heart/spade/arrowboth/arrowleft/arrowup/arrowright
  /arrowdown/degree/plusminus/second/greaterequal/multiply
  /proportional/partialdiff/bullet/divide/notequal/equivalence
  /approxequal/ellipsis/arrowvertex/arrowhorizex/carriagereturn
  /aleph/Ifraktur/Rfraktur/weierstrass/circlemultiply
  /circleplus/emptyset/intersection/union/propersuperset
  /reflexsuperset/notsubset/propersubset/reflexsubset/element
  /notelement/angle/gradient/registerserif/copyrightserif
  /trademarkserif/product/radical/dotmath/logicalnot/logicaland
  /logicalor/arrowdblboth/arrowdblleft/arrowdblup/arrowdblright
  /arrowdbldown/lozenge/angleleft/registersans/copyrightsans
  /trademarksans/summation/parenlefttp/parenleftex/parenleftbt
  /bracketlefttp/bracketleftex/bracketleftbt/bracelefttp
  /braceleftmid/braceleftbt/braceex
  241/angleright/integral/integraltp/integralex/integralbt
  /parenrighttp/parenrightex/parenrightbt/bracketrighttp
  /bracketrightex/bracketrightbt/bracerighttp/bracerightmid
  /bracerightbt
] def

/patarray [
/leftdiagonal /rightdiagonal /crossdiagonal /horizontal
/vertical /crosshatch /fishscale /wave /brick
] def
/arrowtype 0 def
/fillC 0 def /fillM 0 def /fillY 0 def /fillK 0 def
/strokeC 0 def /strokeM 0 def /strokeY 0 def /strokeK 1 def
/pattern -1 def
/mat matrix def
/mat2 matrix def
/nesting 0 def
/deferred /N def
/c /curveto load def
/c2 { pop pop c } bind def
/C /curveto load def
/C2 { pop pop C } bind def
/e { gsave concat 0 0 moveto } bind def
/F {
  nesting 0 eq { %ifelse
    pattern -1 eq { %ifelse
      fillC fillM fillY fillK setcmykcolor eofill
    }{ %else
      gsave fillC fillM fillY fillK setcmykcolor eofill grestore
      0 0 0 1 setcmykcolor
      patarray pattern get findfont patternfill
    } ifelse
  }{ %else
    /deferred /F def
  } ifelse
} bind def
/f { closepath F } bind def
/K { /strokeK exch def /strokeY exch def
     /strokeM exch def /strokeC exch def } bind def
/k { /fillK exch def /fillY exch def
     /fillM exch def /fillC exch def } bind def
/opc { pop } bind def
/Opc { pop } bind def
/L /lineto load def
/L2 { pop pop L } bind def
/m /moveto load def
/m2 { pop pop m } bind def
/n /newpath load def
/N {
  nesting 0 eq { %ifelse
    newpath
  }{ %else
    /deferred /N def
  } ifelse
} def
/S {
  nesting 0 eq { %ifelse
    strokeC strokeM strokeY strokeK setcmykcolor stroke
  }{ %else
    /deferred /S def
  } ifelse
} bind def
/s { closepath S } bind def
/Tx { fillC fillM fillY fillK setcmykcolor show
      0 leading neg translate 0 0 moveto } bind def
/T { grestore } bind def
/TX { pop } bind def
/Ts { pop } bind def
/tal { pop } bind def
/tld { pop } bind def
/tbx { pop exch pop sub /jwidth exch def } def
/tpt { %def
  fillC fillM fillY fillK setcmykcolor
  moveto show
} bind def
/tpj { %def
  fillC fillM fillY fillK setcmykcolor
  moveto
  dup stringwidth pop
  3 -1 roll
  exch sub
  1 index spacecount
  dup 0 eq { %ifelse
    pop pop show
  }{ %else
    div 0 8#040 4 -1 roll widthshow
  } ifelse
} bind def
/u {} def
/U {} def
/*u { /nesting nesting 1 add def } def
/*U {
  /nesting nesting 1 sub def
  nesting 0 eq {
    deferred cvx exec
  } if
} def
/w /setlinewidth load def
/d /setdash load def
/B {
  nesting 0 eq { %ifelse
    gsave F grestore S
  }{ %else
    /deferred /B def
  } ifelse
} bind def
/b { closepath B } bind def
/z { /align exch def pop /leading exch def exch findfont
     exch scalefont setfont } bind def
/tfn { exch findfont
     exch scalefont setfont } bind def
/Pat { /pattern exch def } bind def
/cm { 6 array astore concat } bind def
/q { mat2 currentmatrix pop } bind def
/Q { mat2 setmatrix } bind def
/Ah {
  pop /arrowtype exch def
  currentlinewidth 5 1 roll arrowhead
} bind def
/Arc {
  mat currentmatrix pop
    translate scale 0 0 1 5 -2 roll arc
  mat setmatrix
} bind def
/Arc2 { pop pop Arc } bind def
/Bx {
  mat currentmatrix pop
    concat /y1 exch def /x1 exch def /y2 exch def /x2 exch def
    x1 y1 moveto x1 y2 lineto x2 y2 lineto x2 y1 lineto
  mat setmatrix
} bind def
/Rr {
  mat currentmatrix pop
    concat /yrad exch def /xrad exch def
    2 copy gt { exch } if /x2 exch def /x1 exch def
    2 copy gt { exch } if /y2 exch def /y1 exch def
    x1 xrad add y2 moveto
    matrix currentmatrix x1 xrad add y2 yrad sub translate xrad yrad scale
    0 0 1 90 -180 arc setmatrix
    matrix currentmatrix x1 xrad add y1 yrad add translate xrad yrad scale
    0 0 1 180 270 arc setmatrix
    matrix currentmatrix x2 xrad sub y1 yrad add translate xrad yrad scale
    0 0 1 270 0 arc setmatrix
    matrix currentmatrix x2 xrad sub y2 yrad sub translate xrad yrad scale
    0 0 1 0 90 arc setmatrix
    closepath
  mat setmatrix
} bind def
/Ov {
  mat currentmatrix pop
    concat translate scale 1 0 moveto 0 0 1 0 360 arc closepath
  mat setmatrix
} bind def
end
%%EndResource
%%EndProlog
%%BeginSetup
%PDX g 3 3 0 0
%%IncludeFont: ArialMT
PDXDict begin
%%EndSetup
%%Page: 1 1
%%BeginPageSetup
/_PDX_savepage save def

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/rightdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/leftdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  2 setlinewidth stroke
} bind
/horizontal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/vertical true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/crosshatch true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 30 7.5 lineto
  0 22.5 moveto 30 22.5 lineto
  7.5 0 moveto 7.5 7.5 lineto
  7.5 22.5 moveto 7.5 30 lineto
  22.5 7.5 moveto 22.5 22.5 lineto
  1 setlinewidth stroke
} bind
/brick true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  0.5 setlinewidth stroke
} bind
/crossdiagonal true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  1 setlinecap
  0 7.5 moveto 0 15 7.5 270 360 arc
  7.5 15 moveto 15 15 7.5 180 270 arc
  0 7.5 moveto 7.5 7.5 7.5 180 360 arc
  0.5 setlinewidth stroke
} bind
/fishscale true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  1 setlinecap 0.5 setlinewidth
  7.5 0 10.6 135 45 arcn
  22.5 15 10.6 225 315 arc
  stroke
  7.5 15 10.6 135 45 arcn
  22.5 30 10.6 225 315 arc
  stroke
} bind
/wave true definepattern pop

WinAnsiEncoding /_ArialMT /ArialMT RE

newpath 2 setlinecap 0 setlinejoin 2 setmiterlimit
[] 0 setdash
20 27 moveto 20 784 lineto 591 784 lineto 591 27 lineto closepath clip
newpath
%%EndPageSetup
-1.42109e-016 1 0.811765 0 k
0.5 w
188.933 284.045 30.4574 36.6189 [1 0 0 1 0 0] Bx
b
0.364706 0.686274 -1.42109e-016 0 k
135.767 774.807 33.5247 614.287 [1 0 0 1 0 0] Bx
b
0.796078 0.203922 0.67451 0 k
406.709 769.695 223.695 512.045 [1 0 0 1 -23.71 -0.9483] Bx
b
0.74902 0.431373 -1.42109e-016 0 k
406.709 769.695 223.695 512.045 [1 0 0 1 174.6 -1.46] Bx
b
[0 1 -1 0 224.5 8.206] e
103.049 121.48 103.049 121.48 tbx
0 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Telescope & Dome) 103.049 110.62 tpt
T
[0 1 -1 0 726.5 577.7] e
91.8027 649.049 91.8027 649.049 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(ANU GSL) 91.8027 638.189 tpt
T
[0 1 -1 0 857.2 302.7] e
314.691 572.368 314.691 572.368 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(EOS GSL) 314.691 561.508 tpt
T
[0 1 -1 0 1054 98.25] e
512.018 563.166 512.018 563.166 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Toptica GSL) 512.018 552.306 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
293.22 616.332 234.942 526.359 [1 0 0 1 -23.71 -0.9483] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 -24.73 138.6] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 81.6 0.5853] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 78.53 137.6] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 175.7 -2.482] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 176.7 136.6] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 -111.4 -345.1] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 -197.3 -481] Bx
b
293.22 616.332 234.942 526.359 [1 0 0 1 -196.3 -344] Bx
b
[0 1 -1 0 335.9 39.74] e
151.894 193.528 151.894 193.528 tbx
0 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Power Supply ) 151.894 182.668 tpt
(\r) TX
(\(1.1.12,13,14\)) 151.894 169.668 tpt
T
[0 1 -1 0 118.8 -2.938] e
66.5426 56.9662 66.5426 56.9662 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Telescope) 66.5426 46.1062 tpt
T
[0 1 -1 0 256.3 142.2] e
69.3876 192.58 69.3876 192.58 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Dome) 69.3876 181.72 tpt
T
[0 1 -1 0 863.2 176.3] e
370.013 537.778 370.013 537.778 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Thermo-) 370.013 526.918 tpt
(\r) TX
(Scientific) 370.013 513.918 tpt
(\r) TX
(Cooler) 370.013 500.918 tpt
T
[0 1 -1 0 1005 322.3] e
358.633 674.34 358.633 674.34 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(TermoTek ) 358.633 663.48 tpt
(\r) TX
(Cooler) 358.633 650.48 tpt
T
[0 1 -1 0 767.4 276.8] e
263.799 535.881 263.799 535.881 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Electronics ) 263.799 525.021 tpt
(\r) TX
(Cabinet) 263.799 512.021 tpt
T
[0 1 -1 0 907.8 423.8] e
257.16 675.288 257.16 675.288 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Laser Head) 257.16 664.428 tpt
T
[0 1 -1 0 961.8 74.83] e
463.9 533.984 463.9 533.984 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Electronics ) 463.9 523.124 tpt
(\r) TX
(Cabinet) 463.9 510.124 tpt
T
[0 1 -1 0 1109 222.8] e
454.416 676.236 454.416 676.236 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(Laser Head) 454.416 665.376 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
1 0 0 1 0 0 cm
130.082 271.292 m
130.082 564.331 L
Q
S
q
1 0 0 1 0 0 cm
130.082 564.331 m
83.6128 564.331 L
Q
S
q
1 0 0 1 0 0 cm
83.6128 564.331 m
83.6128 610.594 83.6128 614.594 L2
Q
S
q
1 0 0 1 0 0 cm
83.6128 564.331 83.6128 614.594 4 2 Ah
Q
q
1 0 0 1 0 0 cm
205.743 713.222 209.743 713.222 m2
140.514 713.222 L
Q
S
q
1 0 0 1 0 0 cm
140.514 713.222 209.743 713.222 4 1 Ah
Q
q
1 0 0 1 0 0 cm
140.514 713.222 m
140.514 272.241 L
Q
S
q
1 0 0 1 0 0 cm
206.691 573.819 210.691 573.815 m2
150.257 573.878 L
Q
S
q
1 0 0 1 0 0 cm
150.257 573.878 210.691 573.815 4 1 Ah
Q
q
1 0 0 1 2.845 0 cm
147.152 573.815 m
147.152 271.292 L
Q
S
q
1 0 0 1 3.793 0 cm
157.584 272.241 m
157.584 492.257 L
Q
S
q
1 0 0 1 0 0 cm
161.591 492.343 m
298.887 492.257 L
Q
S
q
1 0 0 1 0 0 cm
298.887 492.257 m
298.887 714.17 L
Q
S
q
1 0 0 1 0 0 cm
298.887 714.17 m
309.693 714.25 313.693 714.28 L2
Q
S
q
1 0 0 1 0 0 cm
298.887 714.17 313.693 714.28 4 2 Ah
Q
q
1 0 0 1 3.793 0.9483 cm
168.016 271.292 m
168.035 474.21 L
Q
S
q
1 0 0 1 0 0 cm
171.829 475.159 m
343.46 475.187 L
Q
S
q
1 0 0 1 0 0 cm
343.46 475.187 m
343.46 523.346 343.46 527.346 L2
Q
S
q
1 0 0 1 0 0 cm
343.46 475.187 343.46 527.346 4 2 Ah
Q
q
1 0 0 1 0 0 cm
181.547 263.013 m
203.027 263.013 L
Q
S
q
1 0 0 1 0 0 cm
203.027 263.645 m
203.027 456.334 L
Q
S
q
1 0 0 1 0 0 cm
203.027 456.334 m
420.987 456.334 L
Q
S
q
1 0 0 1 0 0 cm
420.987 456.334 m
420.987 519.933 420.987 523.933 L2
Q
S
q
1 0 0 1 0 0 cm
420.987 456.334 420.987 523.933 4 2 Ah
Q
q
1 0 0 1 0 0 cm
181.547 251.009 m
215.663 251.009 L
Q
S
q
1 0 0 1 0 0 cm
215.663 251.009 m
215.663 441.171 L
Q
S
q
1 0 0 1 0 0 cm
215.663 441.171 m
474.056 441.171 L
Q
S
q
1 0 0 1 0 0 cm
474.056 441.171 m
474.056 712.2 L
Q
S
q
1 0 0 1 0 0 cm
474.056 712.2 m
473.633 712.2 469.633 712.2 L2
Q
S
q
1 0 0 1 0 0 cm
474.056 712.2 469.633 712.2 4 2 Ah
Q
[0 1 -1 0 480.6 440.3] e
125.32 396.948 125.32 396.948 tbx
0 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(??) 125.32 386.088 tpt
T
[0 1 -1 0 516.6 288.1] e
179.652 343.247 179.652 343.247 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(1 \(2.2.5\)) 179.652 332.387 tpt
T
[0 1 -1 0 556.4 291.2] e
194.814 395.052 194.814 395.052 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(1 \(2.2.6\)) 194.814 384.192 tpt
T
[0 1 -1 0 728.2 382.8] e
159.435 577.633 159.435 577.633 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(2+/- 1 \(2.2.4\)) 159.435 566.773 tpt
T
[0 1 -1 0 859.6 553.4] e
150.591 717.254 150.591 717.254 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(1 \(2.2.1\)) 150.591 706.394 tpt
T
[0 1 -1 0 679.1 -21.14] e
413.406 460.756 413.406 460.756 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(1 \(3.2.2\)) 413.406 449.896 tpt
T
[0 1 -1 0 652.4 -25.93] e
467.738 449.384 467.738 449.384 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(??) 467.738 438.524 tpt
T
%%PageTrailer
_PDX_savepage restore
%%Trailer
end
showpage
%%EOF
