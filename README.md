{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;\red28\green0\blue207;
\red255\green255\blue255;\red0\green0\blue0;\red24\green62\blue13;}
{\*\expandedcolortbl;;\csgenericrgb\c0\c0\c0;\csgray\c100000;\csgenericrgb\c11000\c0\c81000;
\cssrgb\c100000\c100000\c100000;\cssrgb\c0\c0\c0;\cssrgb\c11373\c30196\c5882;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\ri-340\partightenfactor0
\ls1\ilvl0
\f0\fs24 \cf0 Title: A social sensor for detecting drinking-water shortage incidents\
Topics: social media mining, natural language processing\
\
1) Objective\
- To detect and process tweets on drinking-water incidents via mining the social media\
- To develop a systematic method to analyse and classify water-related media on the web.\
\
2) Expected results\
- a standalone social sensor for water issues in North Africa\
- collected data\
\
3) Schedule\
February 2019\
mining tweets (French and Arabic) using Twitter api\
Pre-processing of the data (urls, extract place names from the tweet text, etc.)\
\
March 2019\
Natural language processing of French text using regular expressions, nltk, wrod2vec \
\
4) Encountered issues\
nltk\
- 
\f1\fs22 \cf2 \cb3 nltk.corpus.stopwords.words(\cf4 'french'\cf2 ) 
\f0 is not complete, e.g. \'93les\'94 is not included.\
\
\
\ls1\ilvl0
\fs24 5) References\
Nltk library:\
https://www.nltk.org/book\
\
Regular expressions in python:\
https://docs.python.org/3/library/re.html\
\
Twitter api:\
Mining the Social Web, M. Russell and M. Klassen, O\'92Reily 2019\
https://developer.twitter.com/en/docs/api-reference-index.html\
\
Social sensing\
\pard\pardeftab720\partightenfactor0
\cf0 \cb5 \expnd0\expndtw0\kerning0
Earthquake Shakes Twitter Users: Real-time Event Detection by Social Sensors, Sakaki et. al. In: {\field{\*\fldinst{HYPERLINK "http://www2010.org/www/"}}{\fldrslt \cf7 \cb1 \ul \ulc7 WWW '10}}\cb1  Proceedings of the 19th international conference on World wide web, pp. 851-860, 2010}