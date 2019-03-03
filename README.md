# URT_comm.github.io

## FlowBuilder 'Flow' project - 'URT Comm.' - 'U'niversal 'R'esource 'T'opic-based Communication - "urtc_app@1.0.1"

### Push communication 'data' as per below:-

#### MOTECHAT
##### - Go to 'msg.topic' in the 'injector' node
##### - Replace 'URT' with the MChat 'service' you intend to use, for e.g. ss://, mms://...

---

#### MAIL
##### Go to 'msg.topic' in the 'injector' node
##### Replace 'URT' with 'mail', i.e. mail://
##### Key in the required fields as per below:-
##### - 'From' ID inside (), for e.g. (info@abc.com)
##### - 'To' ID inside [], for e.g. [info@xyz.com] 
##### - 'Cc' ID inside <>, for e.g. <<tom@xyz.com>>
##### - 'Bcc' ID inside 'Aa', for e.g. Amary@xyz.coma
##### - Mail 'Subject' inside 'Bb', for e.g. Binfo@abc.comb
##### - Mail 'Body' inside 'Cc', for e.g. Cbody comes herec
##### - Mail 'Attachment' inside 'Dd', for e.g. DC:\test\file.exed

---

#### TWEET
##### Go to 'msg.topic' in the 'injector' node
##### Replace 'URT' with 'tweet', i.e. tweet://
##### Key in the required fields as per below:-
##### - Tweet target 'Screen_Name (alias/ hashtag)' inside 'Ee', for e.g. E@henrye
##### - Tweet 'Text' inside 'Ff', for e.g. FIt's a fine morning!f 
##### - Tweet 'Image' inside 'Gg', for e.g. GC:\test\file1.pngg
##### - Tweet 'URL' inside 'Hh', for e.g. Hhttp://def.comh

---

#### SMS
##### Go to 'msg.topic' in the 'injector' node
##### Replace 'URT' with 'sms', i.e. sms://
##### Key in the required fields as per below:-
##### - Target SMS 'Number' inside 'Ii', for e.g. I+919876543210i
##### - SMS 'Message' inside 'Jj', for e.g. JHi John! Let's meet up at 11j 

---

#### PLOT
##### Go to 'msg.topic' in the 'injector' node
##### Replace 'URT' with 'plot', i.e. plot://
##### Key in the required fields as per below:-
##### - ThingSpeak Channel 'Field ID' inside 'Kk', for e.g. K1k

---

#### MQTT PUB (using 'broker.hivemq.com' broker on '1883' with 'hj_ypc' open topic)
##### Go to 'msg.topic' in the 'injector' node
##### Replace 'URT' with 'pub', i.e. pub://
##### Key in the required fields as per below:-
##### - 'QoS' value inside 'Ll', for e.g. L2l
##### - 'Retain' value inside 'Mm', for e.g. MNom
