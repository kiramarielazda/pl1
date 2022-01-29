# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=place_id%3AChIJ0eAbuXJ0hlQRCI7kPC_UJ_I&destination=place_id%3AChIJj5efACYDh1QRP3Nqc3p9n8M
&departure_time=now&traffic_model=pessimistic&waypoints=via%3Aplace_id%3AChIJDZ44NDtvhlQRpGV7zxZYWmo%7Cvia%3Aplace_id%3AChIJQd2nCD74hlQRq2GXED0I15A&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```
I decided to calculate the route from my apartment in Vancouver to a favorite climbing spot of ours in Cheakamus, while passing through our friend's neighbourhood to pick her up and stopping at our favorite climbing store in Squamish on the way. I used 'via' though so that I could still enable some traffic modeling to be done and since we hate getting our hopes up when driving anywhere here, I set the trafic model to pessimistic so that we could potentially be pleasantly surprised!
## Next paste the full JSON response to this query here:

```Version:0.9
StartHTML:0000000457
EndHTML:0000042029
StartFragment:0000000493
EndFragment:0000041993
SourceURL:https://maps.googleapis.com/maps/api/directions/json?origin=place_id%3AChIJ0eAbuXJ0hlQRCI7kPC_UJ_I&destination=place_id%3AChIJj5efACYDh1QRP3Nqc3p9n8M&departure_time=now&traffic_model=pessimistic&waypoints=via%3Aplace_id%3AChIJDZ44NDtvhlQRpGV7zxZYWmo%7Cvia%3Aplace_id%3AChIJQd2nCD74hlQRq2GXED0I15A&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE

{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ0eAbuXJ0hlQRCI7kPC_UJ_I",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJDZ44NDtvhlQRpGV7zxZYWmo",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJQd2nCD74hlQRq2GXED0I15A",
         "types" : [ "clothing_store", "establishment", "point_of_interest", "store" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJj5efACYDh1QRP3Nqc3p9n8M",
         "types" : [ "establishment", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 49.9056317,
               "lng" : -123.0225651
            },
            "southwest" : {
               "lat" : 49.2326111,
               "lng" : -123.2739748
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "109 km",
                  "value" : 108516
               },
               "duration" : {
                  "text" : "1 hour 43 mins",
                  "value" : 6190
               },
               "duration_in_traffic" : {
                  "text" : "2 hours 25 mins",
                  "value" : 8699
               },
               "end_address" : "Conroy Forest Service Road, BC V0N 1H0, Canada",
               "end_location" : {
                  "lat" : 49.9056317,
                  "lng" : -123.1626638
               },
               "start_address" : "178 E Woodstock Ave, Vancouver, BC V5W 2S5, Canada",
               "start_location" : {
                  "lat" : 49.2336148,
                  "lng" : -123.1023668
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "60 m",
                        "value" : 60
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 49.2335995,
                        "lng" : -123.1015344
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eE Woodstock Ave\u003c/b\u003e toward \u003cb\u003eMain St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "a}nkHxljnV?a@@eC"
                     },
                     "start_location" : {
                        "lat" : 49.2336148,
                        "lng" : -123.1023668
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "52 m",
                        "value" : 52
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 49.23313419999999,
                        "lng" : -123.101516
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMain St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_}nkHpgjnVV@dAC"
                     },
                     "start_location" : {
                        "lat" : 49.2335995,
                        "lng" : -123.1015344
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 km",
                        "value" : 4674
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 529
                     },
                     "end_location" : {
                        "lat" : 49.2331128,
                        "lng" : -123.0374799
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003eE 41st Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aznkHngjnVR?@w@@oA@eDBwA@w@?gC?]AC?EEM@_FByDD_J?oB@cCBM@G?O@[B}EBwF?_@@w@BiE@}E?u@Ec@BmC@aD@aE?}@DaMBuF?Y?_@?_@?U?k@@s@?{@BEBE?E@Q?qA@aA@aC?iC@yB?_@@}E?g@?oB?eDBeD?mB@w@@{E@iC@mC@yG?eC?W@_B@mBAo@?U?CAWC[?KCOEi@IgAEe@C_@E[AO?QK_BASCKCM@{E?u@?gC@mB?{A?cCB{C@wC?e@@oD@eD?q@@c@@_EAi@@mB?mB@sB@{C?e@?yE@w@?wA?_@?o@?m@?_@@oC?cC?WAoAAk@AKGmAOiC@c@Ao@?M?eA?]@yA?[Ao@@mBC]?wA?w@@mB?uB?S?mC@iCA{CEu@?_B?iC?k@?SA_@AYAKAOEa@OoA"
                     },
                     "start_location" : {
                        "lat" : 49.23313419999999,
                        "lng" : -123.101516
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1522
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 200
                     },
                     "end_location" : {
                        "lat" : 49.2443846,
                        "lng" : -123.0258665
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eJoyce St\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "}ynkHfw}mVGa@Ke@EOEMEMEIEICEAEQWo@u@OOEGUWa@a@SSo@q@OMOQQOWQWUeBaB[[][OO{@{@cAcAc@c@_AaAEYWYc@]a@]a@c@m@k@gAeAu@s@KKeAaAgD{CQC][EEMKiAgAKOqAqAuCoCOOOOm@k@uAsAEEMOcC}BOSuBoBUQm@q@OUCECG"
                     },
                     "start_location" : {
                        "lat" : 49.2331128,
                        "lng" : -123.0374799
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 126
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 49.24445,
                        "lng" : -123.0241796
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE 29th Ave\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "k`qkHtn{mVKm@AM?KAM?G?c@?]HWC[?]?cAAGAS"
                     },
                     "start_location" : {
                        "lat" : 49.2443846,
                        "lng" : -123.0258665
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1740
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 228
                     },
                     "end_location" : {
                        "lat" : 49.2597843,
                        "lng" : -123.0235404
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBoundary Rd N\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y`qkHbd{mVCQCOCQGY@e@O?e@@kCAe@?a@?c@?Y?]AeAAgA@kDGkB@oA@o@A}@AcAA}@@gACQ?]?U?I?C?cA?iAAQ?u@?O@uA?_@?oB@g@?_@Ce@?kB?kBAe@Ag@?Y?cF@c@?G?c@?a@?e@A]Ag@@qA@Q?C?MA]AY?qCBe@?eABW@"
                     },
                     "start_location" : {
                        "lat" : 49.24445,
                        "lng" : -123.0241796
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.4 km",
                        "value" : 5415
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 269
                     },
                     "end_location" : {
                        "lat" : 49.3054336,
                        "lng" : -123.0276862
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to merge onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-1 W\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "s`tkHb`{mVWQMMIQAEEMGUGQKSACW_@A?]W?AKAKAW?G@OBSHOJMNKNABILENGRATGTQ|@GXGV_@|@MNCDIJg@l@GFe@`@?@SNKHKHSNWPKFIFe@VCBSXOD[JWHQDKBMBSBUDOBS@YBW@i@ByBLG?uBNe@B?@]BG@c@FQDe@Hi@Ja@Jk@RC?qAd@[LoFtBeA`@YJk@T_C~@u@XuB|@aAf@IFULeCtAs@`@mAv@cAn@kBnAu@f@IDm@^e@Vo@Zg@Rk@RWJUFUFi@NOFu@Lm@Hm@@aA@[@s@AS?aBAoD@mDByA?mA?c@@cA?uE@i@@O@]@a@DqAVoARiALy@D}@Dc@@k@?g@?WAA?]EA?A?UEa@Ii@Ok@Sc@SYOUQMG?ACA[WQO_@_@c@c@m@w@g@m@cCaDaAmACEoA_Bc@k@e@m@}ByC[a@GOIKSUIKIKQSCC[YYSECKGUKWIMEYEq@G{@A{A?sFDiAB_@?g@@c@?c@?c@@c@?c@@c@?c@@c@?Q?c@@c@?oCBc@?O@{A@oCBc@?E?aA@C?U?c@@gA?c@@k@?eCBc@?gA@S?O?c@@c@?}ABE?oAB_@@[Ba@D[DeATWJIBKBMFOFMFOHE@GDi@\\i@ZWPKDKHIDIDIDKFMFEBOFODODEB"
                     },
                     "start_location" : {
                        "lat" : 49.2597843,
                        "lng" : -123.0235404
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.8 km",
                        "value" : 5768
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 257
                     },
                     "end_location" : {
                        "lat" : 49.3320969,
                        "lng" : -123.083468
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-1 W\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "}}|kH`z{mV]Nc@HK@a@FY@Q@]@W?i@?]?OAS?U?m@AY?UAa@?y@C[CaHIy@?]?[?K?e@@Q?YBQ@YFSDUHYHQJi@\\QNYVUXGFCDABMPOXQXMZEHGPWx@Y~@]nAAHOd@ENK^eAdE[nA{@dDk@vBABi@jBo@hCOx@e@hBa@|AUn@a@hAGNiAvBA@MTORMTGHGFORQPORQNQPQNMLOJ{@n@cAn@MVSNgBpA}AdA}F`Ei@^}@r@g@\\q@d@q@d@m@`@cBjAwEfD_@VqBxAgBnA_Ap@ED]XA?]\\A@e@f@QT[b@MPKPkAtBIPGLGN?@GTABK^Sl@Qp@yApHOx@Mr@Q`AMh@G\\]xA?@_@tA[dAWr@Sd@i@lAUb@_@p@UZILW^_@f@a@f@_Az@YXA@KHMJkAbAw@p@QNEDQR_@b@k@r@SXQXA@g@x@u@|A_@z@[x@Od@Qf@Ql@Oh@Op@Kj@Kj@Ib@Ib@ANMx@E\\?@KbA?HCPAPEh@A\\ATAZ?R?F?PAP?J?d@@^@vA@F@t@?J?LBjBBjA?F?@BlBBbB?JBpBD|D?@C~H?lC?zC?`A@zE?~EAdCAdDChIArGAhGAHAbEEdDExEAxA?`B?H@fB@jBBlD@zC"
                     },
                     "start_location" : {
                        "lat" : 49.3054336,
                        "lng" : -123.0276862
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 292
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 49.3322716,
                        "lng" : -123.0874663
                     },
                     "html_instructions" : "Take exit \u003cb\u003e17\u003c/b\u003e for \u003cb\u003eWestview Dr\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "sdblHtvfnVG`@ANE\\A\\CdBAz@ATC|@?p@A\\?\\?nA@p@?p@?j@?XATA|@"
                     },
                     "start_location" : {
                        "lat" : 49.3320969,
                        "lng" : -123.083468
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 502
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 63
                     },
                     "end_location" : {
                        "lat" : 49.3365535,
                        "lng" : -123.0880903
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork and merge onto \u003cb\u003eWestview Dr\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "ueblHtognVOx@CLCDCDEHQTi@?cCDQPkA@wBCeAAkACO?w@?SAuAA{AC"
                     },
                     "start_location" : {
                        "lat" : 49.3322716,
                        "lng" : -123.0874663
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 722
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 58
                     },
                     "end_location" : {
                        "lat" : 49.34272319999999,
                        "lng" : -123.0858299
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eDelbrook Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m`clHpsgnVgAAgBAS?A?wC@U?wAAq@Be@@]AMAIAICGCIEICGEGEIGiCcBuDcCcBkAkAu@gAo@"
                     },
                     "start_location" : {
                        "lat" : 49.3365535,
                        "lng" : -123.0880903
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 183
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 62
                     },
                     "end_location" : {
                        "lat" : 49.34359,
                        "lng" : -123.0873526
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEvergreen Pl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_gdlHlegnVEt@Ev@Et@Cd@CRCPENGLCHCBIHGHGDA@MBI@O?G?EAIEEGECAAC?C@C@CB"
                     },
                     "start_location" : {
                        "lat" : 49.34272319999999,
                        "lng" : -123.0858299
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 183
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 49.34272319999999,
                        "lng" : -123.0858299
                     },
                     "html_instructions" : "Make a \u003cb\u003eU-turn\u003c/b\u003e",
                     "maneuver" : "uturn-left",
                     "polyline" : {
                        "points" : "mldlH|ngnVBCBABAB?@@DBDFHDD@F?N?HALC@AFEFIHIBCBIFMDOBQBSBe@Du@Dw@Du@"
                     },
                     "start_location" : {
                        "lat" : 49.34359,
                        "lng" : -123.0873526
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 722
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 78
                     },
                     "end_location" : {
                        "lat" : 49.3365535,
                        "lng" : -123.0880903
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDelbrook Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_gdlHlegnVfAn@jAt@bBjAtDbChCbBHFFDFDHBHDFBHBH@L@\\@d@Ap@CvA@T?vCA@?R?fB@fA@"
                     },
                     "start_location" : {
                        "lat" : 49.34272319999999,
                        "lng" : -123.0858299
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 472
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 49.332316,
                        "lng" : -123.0882458
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eWestview Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m`clHpsgnVzABtA@R@v@?N?jABdA@vBBjAAPFjBB\\@lA@"
                     },
                     "start_location" : {
                        "lat" : 49.3365535,
                        "lng" : -123.0880903
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "14.2 km",
                        "value" : 14206
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 592
                     },
                     "end_location" : {
                        "lat" : 49.3620014,
                        "lng" : -123.264639
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to merge onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-1 W\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "_fblHptgnV@l@?N?f@?F?F@d@?h@@T@\\@`@Bh@?BD|@@j@Bf@Br@@R?T@Z@\\A^Az@?x@?`BAtAAjA?b@?T?`@Ah@?b@?Z?X@LDNCr@CzA?PEbDCjAAr@?TCbBC~CCxBAb@EfCA\\At@GrDC`AA`AAV?N?NCd@OnLCtB?bCAzB?@?|BApB?pF?pA?pC?jB?r@?zA?fA?fAA~C?B?|C?vD?nA?jB?v@?x@?jD?pA?lA?`D?Z?dA?d@?b@A`@Ah@Ab@A`@E`@Eb@G`@I`@I^M\\KZO\\MZ]r@a@t@o@lAa@t@u@tAQ\\q@lAc@|@CD_@r@Yh@GLCHsEjJm@rACB]r@Yp@Q\\EJGPO\\MZADKVK\\M\\AFIVK\\I`@K`@GV?DIb@I^G`@E`@Gb@IfAIfACp@ARAhAAfA?t@?P?b@?d@AfA?dA?jAArBCzA?`@AX?LA`@Ab@AXMbEGlBKrDA\\EdAErAARGlBCd@Er@GjBCv@Ct@EdAKrDIhC?BGhBALAR?RCv@Ct@Cf@E|@IhBCZC`@Ip@?DGb@Gd@G^G`@I\\Kb@Ql@Sn@ABO^O^]t@aAjBgAjBu@nAy@tAo@fAm@bAw@|AUh@c@~@[z@]z@Yz@[bAe@hBa@dB]hBY`BS|AS|AQ`CARALCXAFA`@GdAG`AGhAEdAKfAGdAUxEMfCQ|CEz@Cp@KjBCv@?RC`@KfBEfAGhAE~@EbAEhAAbAAfAAdA?fA?b@@b@?\\@h@@b@@V@\\?LLpCJlCHjCHjCBjBBjC@hBClCCfBElBEfAC`AGjAGbAGbAG~@IhAIhAEbAGbAEfAEdACdAAd@CbA?`@Cj@EpBKfGK`FAd@C`@Ab@A`@Cb@Cb@Cb@Cb@Ed@Gf@EXEXGb@I\\I^U~@[`AQd@O\\_@x@_@r@]r@_@t@_@p@]t@]t@]x@KZM^K\\I\\K^G\\I`@Ib@Gf@EXEb@C`@Ed@Cb@Cf@A`@Ab@Ab@Ab@A`@Ab@?JEhCC|BArCAjB?hB@nA?hA?N@xABdBDjCFpC@TJbDL`DR|E\\fIJvBNbDBr@HnBDt@Br@J~BBf@TxELbDBV@`@DbABd@B^@d@Bh@DbA@z@@L@bABfA?`@?^@h@?bA?d@?`@Ad@?D?`@CdAAv@?JCjACbA?HE`BCfAAp@ARChBAd@Cv@Av@EhBGnBC|@C`@EdAGdAGbAEd@I`A?BGt@Gj@G`@MdAE`@EZ?@G`@ObAQbAGb@Q|@EZQ~@CJQbAW~ASbAGd@SfAId@I`@G`@G`@O~@Ij@O`AOfAIj@E`@E^Eb@G`@E^C^Gd@C`@Eb@Eb@E^Ed@C`@Cb@IdAGbAGfACt@Ev@EdAA`@EfAAf@Ad@Af@CpA?f@Aj@AlA?f@?nA?j@?d@?h@@dA?nA@Z?l@@x@?f@?^@dA?`@@f@?`@?b@@b@?b@?b@@`@?^?d@?b@?@@bAAb@?`@Ab@Ab@Ab@Cb@C`@E^E^Gd@G`@G^ETAHK`@ADERKZAFOf@_@lAe@vAGPELYz@KZM\\Wx@IR]dAK`@IVCFIZK`@I^I\\AJERG`@Gb@G`@Eb@E`@Cb@Cf@Cp@EtAAdAChA?p@ARAdAA`@Cd@Cx@Ej@Ef@E\\E`@G`@Ib@S~@IZK^K\\M\\ABKTIRCHOZOXKPCBOVEHKLUXQRED[ZA?URSNSLULSJWJA?SHSFWDYDOBE@Q@u@@g@A]C]G_@EaASk@IGAk@My@Ok@KKCKAs@M]GUCg@Cg@AY?kAHw@Ny@ZA?o@ZGBIFg@\\q@l@MN]`@Yb@SZMPIRUd@KVO\\Od@Sn@Y`AGZA@Ml@GR?@WjAi@zB_@zAUz@w@bDSbAIZIb@Ib@G\\OdAKr@OxAIlAEbACjA?XAR?j@?`@?~@@~@@l@@l@@VDp@"
                     },
                     "start_location" : {
                        "lat" : 49.332316,
                        "lng" : -123.0882458
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "44.6 km",
                        "value" : 44580
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2014
                     },
                     "end_location" : {
                        "lat" : 49.7043933,
                        "lng" : -123.1453252
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBC-99 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "o_hlH~bjoVDn@FhAFt@BZF|@JhADXBXFb@Hr@Jx@Hp@Dd@R|AX~BFb@D`@D`@B`@Bb@Bb@?Z@h@A`@Ab@Ab@C`@E`@E\\CPCRI`@I\\IXCHGVM\\MXO\\OVSZKNEFKJEFMLEDQNQNULGDKFUHYJUFE@OBWDMBC?[DUBWBYDk@DOBG@UBWBWBWBWBUBYBC?Q@WBU?G?O?UAWAIAeAW_@SMCA?IGEGKKQQAAUQEIKKAASWOYOS?ACGIQACO[EIEKACIUKUEIGOEKGOO_@AECCGQEGKWMSGKIOOUU[EEWUGE?AKIGECCECIGOIGE?AUIWMSEAAQCk@IGAQAI?GAU?EAG?c@?_@?g@AWAK?KAA?MAGAMCKAA?GCKCMEGAa@QAAKGKGECA?SQCCGEUSGG]_@e@i@[_@c@i@]a@[_@[]AC[_@W[CE]_@CEu@{@QWII]_@QSg@e@AA_@WGEi@]OIICWMOGQE[Ki@KGAk@GSACAW?G?O?S?C?U@I?M@U@Y?U@W@c@BI?U?o@?WACAQAWEUEUIWIUIUKUKUMGCMGSMA?UMUMSKWMSMUMA?SMUMUMSMMIGEUOCAQKSOUQCAOMMMECSSQUSUQUEGKMOSACQUGIIMOUA?QWGIIKSWQUQWQSAAQSQSSUAAQQe@i@_@a@EEWWOOg@i@a@c@CE{@u@]UMKi@]k@]]SKIg@_@SSQQCCOUQUOWOWIMGIO[OYOWQYQWQUUYy@w@_@_@_@]SQg@e@SSyAuA{@y@?AAAUSeAcAWYIIYSMKGEGEUMUMUIs@SSAYEG?w@GA?QC[AGAOA]AOAA?CASASCKCi@Gm@KWIUIEAOGq@MCA?Aa@Qa@SIEUMECYW_@[]Y_@[i@c@QSAA[_@W[_ByBk@}@AAUa@CCaCyDAAWc@AAcC{Dy@y@c@_@IGIICCAAMM[W?AIGcBiAoBeBSQ][][YWEEWUEE_@]u@q@EEYW][EEGGWWUWEE[_@AASW]e@e@s@MSq@qAy@uAq@iACCs@mAU_@CCYc@AEe@u@KOYa@CESUCEOOSSYS_@WiAu@_Ai@y@e@u@i@g@]UMIECAECUI?ASGSEWESCSAg@?I?SBk@Hm@HQBWDK@K@W@U?MAIAUCC?MCSEUIYISIAAUKKE_@QA?c@OICOEGAMCSCQCQCA?]AC?c@C]AE?}@A}@@S?I?g@ASAA?UCMCMEQESIOGGEQIUOSQOOYYWYUUCEWW?A]YWQIGQMWM[M[MC?a@K]KEAa@KCAm@QWIWM_@SEEQMMKMIQOIISSEEMQGIOSKMKMOWCGQ]Wi@AAOYEOc@aAISUi@Yo@Se@Wk@g@kAEGWi@AC_@q@OWCEW]EGUYACY[GIOOEEKKQQMKQOGEWQEEQMw@e@s@_@i@W]O[KWGYEUEq@EYE_@ECAQEKEKCWMWMGCOKOK]QCAa@UA?YMQGMEGAIAQCGAK?SAC?c@Aw@?s@Ac@?A?YCG?c@CEA]CK?WEKCUCA?EAUCG?OAQAA?G?Y?e@BG?[Bc@@Y@Y?SACAOAOCIAUGCAUIKEGCSKe@WGCYOAAWMYMk@Sm@KYAS@C?W@G@QBWDWFUHOFC@YJC@QFWJSFGBQHSHWFUFSDC@UDWDUDWDWDWBSBM@G?WBWFWDYFUDMBe@LSH[Lg@TmBx@[Je@NWDUFk@FM@c@DA@a@BI@Y@c@@uA@OA[?kA?kAAg@?Y?U@C?YBUBSDSD]Lk@ZGDw@d@i@ZULKFu@d@k@ZULKFq@`@OFo@ZSJIDc@X[Rg@XQHo@\\QHMHa@Vk@`@ED]ZURg@h@STWTUPSLWJUHWFE@KBYBU@W@WC_@Ec@IAAg@M]IKCa@KQCq@Mc@Ia@GeAKgAIi@Ca@AY?w@@q@Fk@Jm@PUF[Nm@Pk@TMDu@Vm@PC@OBUF_@D]ByA?wAAG?u@As@CYCUEWGWI[MQOa@SIGc@WA?]MCAYIGCOCSEKASCCASAOAG?WAC?W?K@Q?WBa@B]DA?a@D]DE?c@DE@m@F]FQ@WBa@?sAAeAA[@AAC?a@A[AG?_@Cg@Ci@Ca@A[Bm@FuAJ]@y@I_@CC?]CEAA?a@EOCS?O?[?G?A?K?I@A?a@FWBKBc@HYFI@SDi@DQ@q@E}@SiAa@_A]o@SKEc@K[Iq@Ke@Eg@@c@@Q@O@e@Bw@Hc@B]@O@O?Q?K?_@?]C_@EE?CAYCSCMCo@KoASk@GUCc@AK?_@@Q@]JMHSJ[R[\\g@l@c@t@U^o@fAMPm@t@k@`@_@LWFUFM@c@F_AJk@DA?_@FOFOHc@VYRgAz@}@l@SNKBi@N]@]?QC]Gg@UoAi@{@YQG_@OaASs@AgARUJ[PQLUPGFGFSXABW^GJQZUb@Q^eArBa@p@CFQXQXQTQRCBGDWPA?QJSHYFA?g@JoAP_@Da@@QAKASCOAKCKAq@Ka@EKASAa@?E?]?MAA?G@Y?G?c@@[?E?a@?e@?a@?A?_@DC@YHWLSNWVIH[\\s@v@q@p@GFKJOJ]TYNSFSDYBY?WCG?KCKCOGYOOE}@WYI[IOAIAK@w@Cm@JUBWDY?S?e@Ha@Ji@H[DI@}@NiAT_@P]Vc@^Y\\Y\\AB[h@]f@c@t@Ud@S\\Yv@AFUz@I\\GT?\\c@lB_@v@[d@QR]ZA?c@XYPg@Xy@f@C@KF[LSHYHW@S?a@AUAe@C_@COAUCOAMAKAQAYAa@AUAC?SCSA_@@_@Ba@DUFODMDo@PYH_@JK@I@K?M@K?GAYAMAKEEAOGICKGOIMKSQIIGIQSIKCECEIOGICEACc@u@Ya@GI[UKIGCGAIAK?MASESGUIYMWKSMQMOKMICAWQOIMESIWEAAk@Ce@Ae@Be@B]Bm@B_@@y@Da@@iAAc@?m@?_@?UBUDQD[LMFQLUL_@Vm@^k@\\wAz@ULg@Vg@VE@C@a@TKBIBKBG@I@C?I?O@SAKCMCOEOEICA?ECWI_@KSEKCIAYC]@_@@UDe@FU@U@UAO@KBIBKBOFKBQFUBi@Jk@JUD_@DSBYDE@I@M@m@BS@sAFC?M@S@A?YBa@BUFWJ_@RQLSTGHEHILGLOXQh@Oj@GXEZG^CNADCNGXEVQv@GZG^I\\ENERCFGPGNKVMRMNUXIHMLi@d@_@^CBUXCBA@KPINGNKVM^K\\Mh@c@nBOn@U|@Wv@C?A?A@A@A@ELIPc@dA_@`AMZYr@]x@[t@m@vAMZO`@[r@ABSd@?@S`@O\\S\\U\\]`@ONQN]PQJIBGBa@JWDg@FA?U@q@FyAVq@NaAJg@HiAP_@FS@_Cd@aARiB\\eAPgARk@H]Fg@F]Di@H_@Dg@DG@u@Da@?U@U@W@{@@m@AM?w@AO?a@CUAMAc@Ca@CA?A?WAK?W@WBKBKB_@DQDSBa@FA?I?KBo@DA?[@G?S@O?UAK?c@?A?EAQ?KA_@Ee@E_@Cg@Gc@EAAa@CIA[Ea@E?Ao@Ki@G[AWA_@CC?gA?M?}ABc@@M?U?c@@Q?K?I?cA@kABcAAYAS@[@UAKAMAUCYGGA?AKCSKA?AASMUUOQSWS[OSKWYs@_@}@O]M[ISSc@Ys@OWOUOMUUOIEAGAG?_@S[MYMOEa@WUK_@SAA_@So@]yA}@]Uy@i@MMQOSQIGECSKUIIEQG[SGCYS_@UaAo@QMMI_@UQMSKWM[OICGCw@Yc@OOGQIMEgAe@OIq@Uq@[WQa@YYSQM]S[UMISKOCKAM@e@E_@EuAOe@I[Ia@O_@WUW[[EISY]q@AACGe@_Aa@}@]s@U_@KMWWKWCCMMY[[_@iAoAm@k@_@]g@c@SSy@u@a@a@KIu@y@a@c@UY_@k@e@o@GK_@k@i@_AIUgAqBYm@A?]cAEGCGEGCEEGIIECOOUUOU_@e@Y[IIQWOSi@s@[a@e@o@EEMQi@s@Y_@W[EI[e@SWGG?AGEOIOKYOCCi@e@OOYYCCKIOUQSW_@IOACAAMWGOAAGQKSISIYAC?AQi@AGM_@Kg@}@aD]iAWy@]s@O[a@q@MOU[QSQQOIMIs@Wg@OMCc@Ms@GSC_@GA?c@K_AQg@WGCi@_@MK[Wa@a@KM[_@m@u@[a@[c@MMm@o@MMo@i@YUiBgAg@Yi@Qo@Oi@K]G{@Mu@I}@E_@Gq@EA?mAEQCq@Ge@Eq@G}@Oe@I_@G[Is@SWE]ASCOEc@McAUwA_@}@QSCs@AgAEk@?_@Ag@By@BuAB_BHYBk@FSFOFyAn@_@RKHONu@^a@Ni@Pe@Hg@DE?c@?iBCiAE]E[Gk@KMEICOG[Og@Ui@USI_@Oe@UWOk@a@e@c@cAgAa@c@WW[Wa@UYM]Kk@K_A[WIWKMIIESMQOOKQOKIIGAASOIGOMc@YCCIEQKKGgAi@a@O_@KOQEE]K[IEA]Ka@IgAQa@IA?{@OIAKCUEIC]K_@O?AUKi@]]Yq@u@SSQUYe@U_@_@i@QUUQIGGCWMi@Sm@Qi@O]Ig@Sg@Si@[QM]Ya@[qAgAk@c@_@YYS[Oe@So@YeBu@[OSKUQ]WIGg@g@q@aA]k@]m@w@wAe@y@Ye@OUW]QS]YEEWSOIa@S_@MAAa@Os@UYGSCGAc@GSEWGg@KeAW}A]m@OMCw@SQEOCiBa@QEiBc@OEoAYm@Mo@Qs@SWGeAYc@KEA]Ig@Kc@Ma@Mc@KcA[A?a@Ky@SKEYGk@MYIk@Oe@O[ICAc@MgAUECa@Kw@Uc@Ki@QEAoCs@]QYMGA_@KYCQEUGGA{@Uk@Sg@Qi@SECYQa@Uy@k@[UIGu@i@IGa@WQMe@[_Aq@_@WGEg@]OI[Oa@QQIC?_@M_@Kw@Se@GUEo@E_AAeBH_@D[Hq@PUFC@GBSHIDYHMDSFUHKDa@NWFMDQFO@IB_@FYBA?e@DOAk@?IAUAOAc@GMCQEA?UEMAs@Mu@Me@GQCQA[EE?c@Ce@@G@S@g@Hy@Tq@Nw@Pk@Jg@Dk@@k@Ai@E}@OWESEAAGASICAa@QA?ECYOA?GGa@]q@o@AASYi@y@M[IQWu@S{@O{@KcAEu@Aw@@gA@W@YB]BWJ_ABS?AHs@@EBSBW?ADc@?G@K?M@U?M?C?SAOAS?GCWAOAECSCMAGEQEQACEQCIGSEKACa@eAu@iBKSO_@OYSYMQ[YGEWQWMUGWAG?c@BWB]HGDa@P_@ZONMPU`@m@fAEJQ\\a@v@Q\\O\\ILWh@y@dBUd@Y^UV]XA@QLUJQHIBUDOBa@BY@G?c@?I?iAEWESCWGUIAAKIUQGISUOQ_@c@KMa@e@WUCA[WGEYMMGEC[ISGo@KuBY[GCA_@KQGAA_@QMGi@_@o@i@SS_@k@w@qAm@gAq@mAOUMYWa@U]Y]s@s@SQaAc@MGCAg@Qs@UUG{@QI?MBm@Ac@BK@I@WHC?s@TsAb@EEA?C?IBUF_@JWLKD]Vw@n@i@Zq@XYFSBOB_@?YAc@Eq@IM?c@?M@A?GDY@WBUB[Jg@RYLa@TGBULKFSJSFIBQDI@I@S?_@EQCQCICWGA?k@O_@GAASAUEA?G?M?I?K?c@@E?YDWDQD[HA@]LcAd@cD~A{@^MFEB_ChAyBdA_Bx@yAr@a@Py@`@WLm@XG@a@Na@Nc@L_@Nc@Na@NG@]NSJMHYTA@{@v@A@a@f@q@z@A@[`@SVGFSTYTUPYPQJOHMFSJQHg@PIBe@LuBf@k@HKBMBUB{@JI@c@DI@Y@C?q@BQAG?[?U?M?[Ea@GGCMEo@Wi@YYQk@i@CAY_@[c@Wa@S[EMO_@]}@Qm@Mm@GSEUGc@I{@CQEu@E_AEoAAUEk@GoACe@E_@EWOcAQw@I]GSEOO_@M]IQOWEI[c@a@m@i@q@gAuAe@g@oAuASS_@]US[Wa@_@IGwAmAKW_@[]Yg@a@}AkAcAk@y@c@m@]yCaBOIQIcB}@w@a@{@e@cCsAa@S}BmA_@O_A_@w@[KG]WCA[YIGYUCCSSACIISYCCSc@CKO_@Us@M_@Ia@M{@Mu@KiAACEq@A}@?AAu@C{AKsFIgDEkBCsACs@KiAK}@AOKs@Mq@WqAMq@AG_@oACGe@mAk@oAg@}@u@iA_AoAKOu@iAYg@S_@CGWi@IQK[Sm@EKKc@I]EQIe@CMKs@COGc@Ku@AKQ}AA?CUE]CIi@mEe@qEIs@?AEYMi@I]CIOe@KYUm@GQQ[EKYg@MYKMYe@Ye@u@iAi@{@]k@EIWi@AC[y@KWQs@Mq@Im@G]MmAKy@ASIo@Ow@COIa@IYA?CIGUUk@GMEKe@_ACE[i@Y_@EG[a@IMKMEESWGIU[a@g@]a@EGq@}@[c@UY[c@EE[c@EGOS[a@EGU]ECw@cAIK{@eAa@e@Y[GK_@m@IMQUo@y@ACEE[a@GGUWIIMOIISQAACCOKIGGC]SgA[QGyAi@iBo@s@_@GEUQAASOc@a@EGQQi@k@OSi@{@U_@_@o@Q_@Ue@AAUg@Yk@AASe@?AUi@?AWk@k@wAQa@CGoAoDQe@Um@Uk@Sk@Um@Uk@Sk@u@qBUg@KUq@iAm@s@cAu@YSk@WGEk@WOG{@a@a@ScAe@ECyAq@SMMGqB{@WMgAg@q@[cAg@CAuAk@OI[Ou@_@MI]Qk@YYQIEk@]]YMIeAw@_As@eBqAuB}AiAy@uAaAECkBuAi@_@e@]eBqA_@Y_@Ys@k@_@Y_@Y_@Y_Au@m@c@i@c@kBuA{@o@k@a@g@a@_Ao@i@a@EEGE[WAAQOQOGGMMQSOOEEQSOSAAMQCCSYEEMOOUGKGKGGKOOUQWGMIMGIIMIMEIS[IOCCQUY_@SUMKUSECWQIEMGWQYMGCYMUGKEYIGAQG[IWGCAi@OA?i@Q[Ig@OQG[GeAYUGSEKCUGy@Si@MgAWUE]K]K}@U[Ia@KUG]Ka@MKESIsAg@g@QiA_@s@WEAOGa@SMEUKYOGCIEWMKEe@USKg@WWOSISICAUISEA?SEMAGAYCY?U?Y@SDM@QDC@c@J]LIB]LSFq@VODwA`@m@NGBOB_@HOBC@YDa@Fi@DgADM@s@@[?W?C?M?KAQ?S?[?g@BQ@K?I@I@KBODUFSFe@PaA\\IBaA\\cA\\WJ"
                     },
                     "start_location" : {
                        "lat" : 49.3620014,
                        "lng" : -123.264639
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1383
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 270
                     },
                     "end_location" : {
                        "lat" : 49.6951201,
                        "lng" : -123.1562932
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCleveland Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m{jnHhyrnV[HDj@PbA`@lDJ~@B`@Fb@Jx@TvAJ`@TbABBh@bAJVR`@j@p@FFh@f@`@X^ZXRPJV@fClBJPHHTPdAv@xAjArBbBbE`D|BhBVPz@n@z@p@lA`An@d@VT\\^nBxAtAfA|BhB"
                     },
                     "start_location" : {
                        "lat" : 49.7043933,
                        "lng" : -123.1453252
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "53 m",
                        "value" : 53
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 49.6949134,
                        "lng" : -123.1556282
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eVancouver St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "oainHx}tnVNg@H_@DWHc@"
                     },
                     "start_location" : {
                        "lat" : 49.6951201,
                        "lng" : -123.1562932
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 406
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 49.6981061,
                        "lng" : -123.1528919
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLoggers Ln\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "e`inHtytnV]W_H}F{EwDeBuA"
                     },
                     "start_location" : {
                        "lat" : 49.6949134,
                        "lng" : -123.1556282
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "57 m",
                        "value" : 57
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 49.6983604,
                        "lng" : -123.1535777
                     },
                     "html_instructions" : "\u003cb\u003eLoggers Ln\u003c/b\u003e turns \u003cb\u003eleft\u003c/b\u003e and becomes \u003cb\u003eVictoria St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "etinHphtnVQv@Of@GTGR"
                     },
                     "start_location" : {
                        "lat" : 49.6981061,
                        "lng" : -123.1528919
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 900
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 162
                     },
                     "end_location" : {
                        "lat" : 49.704286,
                        "lng" : -123.1459112
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCleveland Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wuinHzltnV}BiBcEaDsBcByAkAeAw@UQIIKQgCmBOYSOUQGEiA_AMKEGKMOUU]Uc@MSO[[}@Oi@AKACKg@O}@Ia@CYSkBCSAK]{C"
                     },
                     "start_location" : {
                        "lat" : 49.6983604,
                        "lng" : -123.1535777
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "24.5 km",
                        "value" : 24498
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1128
                     },
                     "end_location" : {
                        "lat" : 49.9056317,
                        "lng" : -123.1626638
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBC-99 N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yzjnH||rnVKkAGg@[HaAZaA\\s@XMDyAf@aAZ_@Jq@Ro@Ts@V[L[Jq@TcAZ[JGBMDk@LKBa@Je@JGBQBG@KBWFYDo@LUBC@E?YDI@A?m@FWBWB_AFQ@I@o@BM@]@i@?G@_A@c@?e@?eA@c@?kBBc@@A?a@Ak@?_A@[?G?c@?kB?O?I@c@?I?cB@G?cA?sA?}DBQ?}@@O?c@?{@?eCByDDQ@}AB}IDO?m@?mB@cA@Y?q@?i@@E?]AA?_@?WAg@Ek@KUG[KUIUMUKUMc@[k@i@c@c@g@s@_@m@Q[Yo@Qc@Wu@Kc@eAuDo@{BKa@Uw@a@wAW{@I[AAa@}As@eCSo@Qo@Qo@Qm@IYIUQo@ACK_@GQOg@Me@Qo@CIMe@So@a@wAUs@Sm@Um@A?KYKUSc@i@cAKQ_@m@KO[a@c@k@SUQQUUSQAAOOUOWQAAc@WYMECOGWKUGUIWGUEGAMCWCa@Cc@Ci@?o@BaA@u@@u@?cDJcAFi@Be@B_@@Y?iAD{@Bw@BeABeABeADo@@M?}@BsCHw@By@B}BHgAB_BDu@BI?}@D]BC?A?a@B{@BaDLqBH_BHkBFG?y@By@B_CFa@@_@@I?kAD}AD{AD}ADqBFU@uBF_@@eCFgINyADC?uAD]@E?_A@eCJoBH_BDqBF{ADc@@a@@A?iBFgBFW@Y@i@BW@YBWBWBUBm@FWDI@_@D[Fk@JYDKB_@HA?k@LYF?@c@HC@_@JODQDc@JKB}A`@o@NSFWFc@JI@WFA?WBI@c@Fe@Di@Da@@mABsA@k@@w@@w@Bo@BC@YBWBYDq@J[FWFYHI@a@LE@UHA?A@CBUNiBb@cA\\KBc@LMDSF]JC@]H[HG@SD]Hw@LSDa@Fq@Ji@Fe@DQBc@DYBE?q@DaADy@BM?K?Y?Y@Q?_@?S?_@AY?K?KAK?QAQASA]CG?a@Ci@Em@Gm@Ik@G]GA?GAKCUC?AMAMCCAm@Kq@O}@Wu@S]KMEa@MSIa@Oq@Wg@SQGyAq@{Ao@QISKKEA?GEKEo@YWKq@][Ms@[OIaAc@]Oe@UcAe@ICIEo@YOIQIi@UYMc@SAAi@UKGUKUKKEq@]QGSK]MSKSIqCgAC?q@Yi@Ou@U}@Yo@QKC]IICOCOEKCMCMCKCMCw@OUGA?}AYs@M}@Ik@Ke@IgCY[EmAMSCmAOIAc@Es@Iu@IoEi@u@IaAKgAOYCa@GWCSCOCYCc@Ea@GIA[CGAc@EIAs@MGAc@Kc@MA?YM[O[QYSSQIGUSGGSUAAMQMOCCQWEGIOOYKUIQIQKYEIOa@Qi@ACKa@Mg@Mk@G_@CKGa@E_@]iCm@mECSG_@]kCCQc@_DEYGc@E[CMEMIc@CKU_AY{@CESm@AA[q@Sa@Yg@_@k@SWIK_@a@a@_@a@[_@U[Q_@QSISIYGYKWE[E]CWAU?Y?W@A?YBG@UBM@I@UDC@UDMBSBMDQBQBODSDQDOBUDMBSDOBQDODQDe@Hm@LC@c@Ho@Ly@Pq@Ls@LWFQBQDSBYBWBY@Y?_@?QA[A[CWE[GYIGAMCSIICe@OUKICWK]Me@Qa@QOEu@YQIOE_@OAAYIGC[KGCg@MYIWCOCGAYCY?SAO?[@Q@G?]@UBQB[Fc@LA?]Jc@Le@LEBs@RID[HG@WH[HQFMDSHSHWJWNULWPQLOLOLWXORQTA?QZEFILMVMTIRIRQf@GTGRK`@Md@I^AFIb@ADGXCPMv@SfAAFOt@Ot@G\\GRIZENGNABGNA@MV?@GLGJOZABOTQRSTSPWRSLSLMFMFi@Vu@^c@R_@P_@Rs@d@uA~@m@`@CBq@d@i@\\m@`@k@`@q@`@q@d@IFSLYTUNSPSRSRUTa@b@WX]d@CBSTKJe@h@c@d@MJSPA@QPOJEDIFYXe@`@UN[RWPGDu@^A@SJYL_@RKDWLSHSHQFQFQDWFMB]J[Fe@H_@Ha@FYFQDOBSD]F]Fe@JG@_@FC@k@L_@Ha@FYFUD[Fc@Ha@H[F_@H[D_@F[F_@F_@FYBG@[DQ@O@A?M@Q@Q@Y?[?U?[Ak@?i@?UA_@?SAg@Ay@?I?_@As@A{AAgACa@?A?M?i@Ag@AK?eA?e@AY?oA?K?S?]?c@@k@?A@Q?Y?W@UBQ@M@SBWD_@FODWFIBc@JWHIBC@YLSFSJYNEBUJMHWNSLSLA@YR[VUROLC@KJOLQRKJWXQPMPOPW\\W\\W\\U\\[d@C@Yb@Yb@[b@w@hA[b@[b@Yb@GFm@~@SXGJQVGJUZc@r@W\\ILSZQVa@j@OTSZUZW\\EFUXMPOTUXCDILOROTOTW\\U\\U\\UZORABOTOVMTMRMPABMTOXKTMXKTIRQd@Wv@Oj@I`@Kb@CLCHAHMj@Kh@ADMp@ADKh@ABMl@Md@I`@K\\?BIVOb@MZ?@MVGP[n@KPILABIPKNMRMPILMLIJSTCBOPKJURKHEDWPA@MJSLYNQHSHWJSFSFSFMBOBIBK@]DYBS@i@DU@G?g@Do@DS@c@BY@I@W@Y@_@DY@C@Y?e@DO@K@YBU@S@U@YDWB[BUBG@UBWBQBW@WB]D[FK@a@JYBa@F]FE?YFI@YFG@QDQDQDYJYJA?QHULYNMHOJA?GFID[VONIHQPQRMPOTMPMRMTGNMPKPKRWf@ABOZMZGLKRMVQ^IPKPMTYh@SZMPWZOPGHOLMLA@SNSNk@ZOHSHOFODSFSDg@LC?c@JQFeATODQDq@Nc@Jc@LA?_@JA?UHKBOFQFIBOFGBa@PA?aAf@cAf@OHYLc@Ti@X_@Pm@XC@_@RgAf@{CzAe@VC@cAf@a@R_@REBYNA?s@`@MHYPED]RCBaC|A?@_@VeAt@o@`@[PYN[L[Lm@N]Fc@Ba@@m@Cs@Gi@Ia@Ii@MQEoB_@iB_@a@Kc@IiB_@eAUa@IAAa@IE?k@KUCYCk@CA?g@?q@@a@Dg@Dm@JC@e@L_@JGBe@PULQFOJOHQJ_@TIBgBfAo@`@a@RA@YJE@QDQDI@YBC@Y@E@WQ[AK?WCm@GYIa@MMCcAa@UKoAm@SK}@a@}@e@EA_@Ua@S]Sc@WMIQMa@W_@YAA]Sa@UGEc@Sc@SUIa@KSGOEQEOHgAMA?WAIASA[C[AQAa@AOCM?SCA?SCSASCSAOAYCWAQAMAK?S?C?K?I@O?Q@YDSBC@SDKBYHSHOF[NULOJC@OJSNWR_@ZQNUNYT_@T[RABIBYNWLa@Pa@LWFMBWD]Dc@BW@I?YAI?c@Ag@EUEOCYGSEGAg@K_@Ia@Ic@K_@I[Gq@GQAUAU?O?K@Y@]D_@F]HSHi@ROFKFoAl@SH[Nq@Zm@ZIDk@V{@^_AZg@Nc@J_@HSDOBi@H_APG?OB[Fi@JKBoCj@cAVWFkB\\q@HWDYD_@BM@M@G@W@C?WBe@Bo@@g@B]?E?]?[?G?]@W@y@@q@Bg@DmAN]Ds@JaANq@H[B]FWBY@UDQ@[BUBC@O@YBWBWBO@E?U@W@U?UCWCUCWEQEWK[Mi@YYMKEWMWKYKSGOCCA"
                     },
                     "start_location" : {
                        "lat" : 49.704286,
                        "lng" : -123.1459112
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 49.3427703,
                        "lng" : -123.0862817
                     },
                     "step_index" : 11,
                     "step_interpolation" : 0.1816259059436705
                  },
                  {
                     "location" : {
                        "lat" : 49.6962871,
                        "lng" : -123.1553134
                     },
                     "step_index" : 17,
                     "step_interpolation" : 0.8932216883147153
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "a}nkHxljnV~AiDXmH?mP\\_{@n@_hB_AuzCyAcx@oa@{a@eZ{XmFyG@eDWkEeIe@_\\Mat@CwF{DwDrFgGfHwIxBiS`Dwf@fVoQrEig@|@gPs@cPuQqK}LgZOco@p@mRzGgWUoJ|C}Uzv@wt@pj@}G`KaKha@aMhN_KrTaAz`@]bdC_@rSkHdAwOQ_SUqQmLk@lGuBXx@TfB}HrUbMt_@PfFJnAfBJ~ELjVQxWaAbhBGxa@kJlUqR~f@yBr`AoAn^kFjR}Qvc@gDdc@kBxb@v@pb@aDtnAuN`g@e@r_@pCn|@rApv@cFvu@oHdm@Y~o@_@nPcEfOqDvN}@jWiD|LqFzEsLKqGiAyIjAmIbNyGpZ]|XzCdZ]bOaEdHoRhCeGeD_CeFaKeIgLcCgK}LyJcFkReBoNuKel@}m@cS}Du[o_@{Ya[eIkLuMcHuQoAyJWiGwDoQuKgOaXiU}I_Qo@gRiCsRnE_OlD_PbAu[fSgKy@wS~@oQ\\_HcCuWd@mVf@sRmCmIA_Ho@uExD{FnF_Ft@kHzDsH}B_HbAwBpDcIpIeLKaI`@gKlGgKaAcGv@}FhE_IjReKrCwRb@}L_JgJaBuNlA{KxF{E}@aVzBoGhHwBnJgMtXkIrQeOfDih@jE{m@YuFyAiHsMsWcOiZqL{JoL_OoOiTa\\cL_OwIgSaOmFuQmMaUkCkViByQtEmQsEsN{IuSkIkKcJsPgJwHuD{GuJgJaGog@uLsa@eLqNmJkFwA}Il@qHrBgJw@}ObAoHaBcEgGq@cLt@}Ii@uEmGwKyD^yCpE_JxLiIu@gIwFwFsAuHgKmFiFwFaAmIpBiMbC_IfCuGy@ii@jTgJ~IiNhDaJcA_HqOoBeSkNgQ_m@}^aDkQcDee@oLyT{C{SkE}QwHgQ_CuLuGkJgSqWkM{FyI{MgKoXsGcHqI_EmSsJa]wV}ZiWoLyL}r@qTiYjE_JtAyDpAdA|I|BdKvQrOrSdPtEtDlFhBmHqIcJmD{R{McLuLyAyGw@gHqBmAaLvDsGxBsI`ByOh@_~@d@oQm@}FsFcF}OcHoVmEwNoHwKeIoCuz@vBujAdDyf@lDoa@xEuYtGaXs@k`Ay^wl@_IkJ}AuFsFqK}j@uJcLkI_@aVtEeVgFeIYyJrCoG|FcDtMcCfI_LlH}YfVsWtJ{V`Dsa@KiQfIgd@nq@iIrXaFrEaIxAsUbBgQrHkNxRwXlJad@hUaXsEyMr@mKlFkMyCuMoHmKqAcOr@mIpFgKHuLy@uQlHo`@dFw\\pBgGaC"
         },
         "summary" : "BC-99 N",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
