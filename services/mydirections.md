# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJ0eAbuXJ0hlQRCI7kPC_UJ_I&destination=place_id:ChIJG3q8d85zhlQRIH1pyAsVpEc&alternatives=true&mode=bicycling&waypoints=optimize:true|place_id:ChIJ7_0WpPdzhlQR2ULoL78zALs|via:place_id:ChIJIcZrTvVzhlQRiKTnD03vt7Q&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
Version:0.9
StartHTML:0000000441
EndHTML:0000034665
StartFragment:0000000477
EndFragment:0000034629
SourceURL:https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJ0eAbuXJ0hlQRCI7kPC_UJ_I&destination=place_id:ChIJG3q8d85zhlQRIH1pyAsVpEc&alternatives=true&mode=bicycling&waypoints=optimize:true|place_id:ChIJ7_0WpPdzhlQR2ULoL78zALs|via:place_id:ChIJIcZrTvVzhlQRiKTnD03vt7Q&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE


{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ0eAbuXJ0hlQRCI7kPC_UJ_I",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ7_0WpPdzhlQR2ULoL78zALs",
         "types" : [ "bar", "establishment", "food", "point_of_interest", "restaurant" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJIcZrTvVzhlQRiKTnD03vt7Q",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJG3q8d85zhlQRIH1pyAsVpEc",
         "types" : [ "establishment", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 49.2727628,
               "lng" : -123.1012067
            },
            "southwest" : {
               "lat" : 49.2336117,
               "lng" : -123.1359572
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "1.5 km",
                  "value" : 1498
               },
               "duration" : {
                  "text" : "6 mins",
                  "value" : 331
               },
               "end_address" : "4298 Main St, Vancouver, BC V5V 3P9, Canada",
               "end_location" : {
                  "lat" : 49.2465203,
                  "lng" : -123.1012067
               },
               "start_address" : "178 E Woodstock Ave, Vancouver, BC V5W 2S5, Canada",
               "start_location" : {
                  "lat" : 49.2336148,
                  "lng" : -123.1023668
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "12 m",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 49.2336117,
                        "lng" : -123.1021964
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eE Woodstock Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "a}nkHxljnV?a@"
                     },
                     "start_location" : {
                        "lat" : 49.2336148,
                        "lng" : -123.1023668
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 101
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 49.2345159,
                        "lng" : -123.1022291
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eE 40th Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "a}nkHvkjnVqA@K?wAB"
                     },
                     "start_location" : {
                        "lat" : 49.2336117,
                        "lng" : -123.1021964
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "47 m",
                        "value" : 47
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 49.2345094,
                        "lng" : -123.1015755
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE 40th Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wbokH|kjnV@aC"
                     },
                     "start_location" : {
                        "lat" : 49.2345159,
                        "lng" : -123.1022291
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1338
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 301
                     },
                     "end_location" : {
                        "lat" : 49.2465203,
                        "lng" : -123.1012067
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMain St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ubokHzgjnVwDDsDF[?y@?s@?k@AsDGU?_DI_AAQOsBGwACqAAiABWFU?mBIk@?y@A}ACs@CsACyCEwFKu@AkBC"
                     },
                     "start_location" : {
                        "lat" : 49.2345094,
                        "lng" : -123.1015755
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "7.3 km",
                  "value" : 7255
               },
               "duration" : {
                  "text" : "25 mins",
                  "value" : 1478
               },
               "end_address" : "Public Market, 1689 Johnston St, Vancouver, BC V6H 3R9, Canada",
               "end_location" : {
                  "lat" : 49.2727628,
                  "lng" : -123.1357365
               },
               "start_address" : "4298 Main St, Vancouver, BC V5V 3P9, Canada",
               "start_location" : {
                  "lat" : 49.2465203,
                  "lng" : -123.1012067
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "61 m",
                        "value" : 61
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 49.2459762,
                        "lng" : -123.101229
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eMain St\u003c/b\u003e toward \u003cb\u003eE 28th Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wmqkHpejnVjBB"
                     },
                     "start_location" : {
                        "lat" : 49.2465203,
                        "lng" : -123.1012067
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 276
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 49.2460505,
                        "lng" : -123.105027
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE 28th Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kjqkHtejnVAbC?|BAv@ApAAvB?XAlBCjB"
                     },
                     "start_location" : {
                        "lat" : 49.2459762,
                        "lng" : -123.101229
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 158
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 49.2458214,
                        "lng" : -123.1070021
                     },
                     "html_instructions" : "At the roundabout, continue straight onto \u003cb\u003eW 28th Ave\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "yjqkHl}jnVA?A?A??@EF?@?@A@?@?@@@?@@DBD@?@??vB?T?R?P?RB`@@P@LBJDNFPJVHT"
                     },
                     "start_location" : {
                        "lat" : 49.2460505,
                        "lng" : -123.105027
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 107
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 49.246591,
                        "lng" : -123.1078765
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePeveril Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kiqkHviknVIHyAfBCBEDk@r@"
                     },
                     "start_location" : {
                        "lat" : 49.2458214,
                        "lng" : -123.1070021
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 200
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 38
                     },
                     "end_location" : {
                        "lat" : 49.2454845,
                        "lng" : -123.1100441
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDinmont Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "enqkHfoknVFHFHHLDJFNRh@v@nBv@rBp@bB"
                     },
                     "start_location" : {
                        "lat" : 49.246591,
                        "lng" : -123.1078765
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 314
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 49.2430163,
                        "lng" : -123.1091505
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ggqkHv|knVFI@A?@BBRj@@B?@@??@@?@?BA@A@ANM@?@?@?@?@?d@m@PU@CDCFEJGBA@APAn@G@?LDF?F@L?j@@LADC@?XYTUXWV[FIBCDAB?B?VJ"
                     },
                     "start_location" : {
                        "lat" : 49.2454845,
                        "lng" : -123.1100441
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 404
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 103
                     },
                     "end_location" : {
                        "lat" : 49.24057699999999,
                        "lng" : -123.1053525
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e29th Ave Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidlothian Ave\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow 29th Ave Bikeway\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{wpkHdwknVZ]FKf@k@LMZ_@|@gAJMnA{ALKxAaBJMBCLSLQHOHQHUDMDODMBO@E@KBSBQ@U@e@?W?["
                     },
                     "start_location" : {
                        "lat" : 49.2430163,
                        "lng" : -123.1091505
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 444
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 49.2445683,
                        "lng" : -123.1051811
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOntario St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "shpkHl_knVc@AyAAc@AA?a@A_@AkAAa@Aa@Ac@AC?y@AuAC{ACiCEC?E?"
                     },
                     "start_location" : {
                        "lat" : 49.24057699999999,
                        "lng" : -123.1053525
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 512
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 73
                     },
                     "end_location" : {
                        "lat" : 49.247697,
                        "lng" : -123.1100927
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePeveril Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qaqkHj~jnV@LAN?FAFAFAFAHCD?@A@?LEDo@v@{@bA]`@aAhAY\\IHyAfBCBEDk@r@MLMNY`@W`@MVKRGLEJMVCFGNK^M\\K^I\\I`@ELCRI`@"
                     },
                     "start_location" : {
                        "lat" : 49.2445683,
                        "lng" : -123.1051811
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1350
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 268
                     },
                     "end_location" : {
                        "lat" : 49.2598355,
                        "lng" : -123.1095786
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eColumbia St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cuqkH`}knV]AkBA}A?W?_@CeAGiBCgBCc@Ac@Aa@?{ACwACuAAyACiBC_BC}AAwACcBCGA}ACE?yAEeBGaBAgA?A?QAkAAQ?cACW?eACq@CY?MAmAA"
                     },
                     "start_location" : {
                        "lat" : 49.247697,
                        "lng" : -123.1100927
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 251
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 49.25988599999999,
                        "lng" : -123.1130302
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_atkHzyknV?`B?`@?t@AnBAbDAlBCtB"
                     },
                     "start_location" : {
                        "lat" : 49.2598355,
                        "lng" : -123.1095786
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 549
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 154
                     },
                     "end_location" : {
                        "lat" : 49.2648199,
                        "lng" : -123.1128271
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eYukon St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eYukon Bikeway\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Yukon St\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iatkHlolnVwACU?G@e@AE?WAC?O?kAAm@Ao@A_A?M?MAM?kACK?c@Ai@?W?m@?AAu@Ac@?_AGUAyAE"
                     },
                     "start_location" : {
                        "lat" : 49.25988599999999,
                        "lng" : -123.1130302
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 828
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 49.2651329,
                        "lng" : -123.1242088
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eW 7th Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "c`ukHdnlnVAtBAxAAb@?RAXC^CZG\\Cb@AL?NAN?ZAf@CzEAjD?x@AxECdEAt@AH?DAF?HA`EClBAlBAbG?zA?X"
                     },
                     "start_location" : {
                        "lat" : 49.2648199,
                        "lng" : -123.1128271
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 138
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 49.2663459,
                        "lng" : -123.124327
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLaurel Street Land Bridge\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "abukHhunnVIBA@GFMNQ@S?[C[?KC[?GA[AK?O?C?A@C?A@"
                     },
                     "start_location" : {
                        "lat" : 49.2651329,
                        "lng" : -123.1242088
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 188
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 49.267001,
                        "lng" : -123.1263023
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eSchool Green\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uiukH`vnnVCBEJCHE^EPETEFIHIHe@b@YPMLO\\AJABAF?B?FAF@J@NF^BNLp@"
                     },
                     "start_location" : {
                        "lat" : 49.2663459,
                        "lng" : -123.124327
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 153
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 49.2674376,
                        "lng" : -123.1277471
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSchool Green\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wmukHjbonVKAOAE@I?KBIBC@EBIHEHGLEPEPAR?D?J?RBTH~@BTFh@"
                     },
                     "start_location" : {
                        "lat" : 49.267001,
                        "lng" : -123.1263023
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "52 m",
                        "value" : 52
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 49.2679045,
                        "lng" : -123.127779
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eIronwork Passage\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "opukHlkonVa@?M?W?G?G@CB"
                     },
                     "start_location" : {
                        "lat" : 49.2674376,
                        "lng" : -123.1277471
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 182
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 49.2678788,
                        "lng" : -123.130004
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eIronwork Passage\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSeaside Bicycle Route\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ksukHrkonVEDCDALAHAL@H?hAAtAAF?B?HCHCFCFGFEDCJAD?H@F?HBFFJT^DJBD@D@H@H@J?F"
                     },
                     "start_location" : {
                        "lat" : 49.2679045,
                        "lng" : -123.127779
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "86 m",
                        "value" : 86
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 49.2675411,
                        "lng" : -123.1306417
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eIsland Park Walk\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSeaside Bicycle Route\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "gsukHnyonVAJAJALAN?^?L?F@D@B@BBDB@J@J?RAPA"
                     },
                     "start_location" : {
                        "lat" : 49.2678788,
                        "lng" : -123.130004
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "40 m",
                        "value" : 40
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 49.2672917,
                        "lng" : -123.1310375
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSeaside Bicycle Route\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eThe Castings\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cqukHn}onVNXDFZl@"
                     },
                     "start_location" : {
                        "lat" : 49.2675411,
                        "lng" : -123.1306417
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 487
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 83
                     },
                     "end_location" : {
                        "lat" : 49.269479,
                        "lng" : -123.1359572
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eIsland Park Walk\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSeaside Bicycle Route\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "qoukH~_pnVHVDR@H@H@H@H@H@FBHAB?BAFAJAHCHAFABELEJGJA@GFs@j@C@QNABCD?DAF?FAd@?@?@CLAJCHEF?@GFMHGHEDEDCFCDCFABABADAHAHAJ?HA\\ANANAJCJAFCFKPEFCDAFAB?BAHAFAFANAHAHA\\ALAJCLETKROJMLCDGJA@C@GFQDKBOBGBIDGFGDGFA@EDGFMT"
                     },
                     "start_location" : {
                        "lat" : 49.2672917,
                        "lng" : -123.1310375
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 132
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 49.2703918,
                        "lng" : -123.1347907
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOld Bridge Walk\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "g}ukHv~pnVYa@?AQWAAY_@CEq@{@w@iA"
                     },
                     "start_location" : {
                        "lat" : 49.269479,
                        "lng" : -123.1359572
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 101
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 49.27108,
                        "lng" : -123.1338849
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOld Bridge St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}bvkHlwpnV]e@kBoC"
                     },
                     "start_location" : {
                        "lat" : 49.2703918,
                        "lng" : -123.1347907
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 225
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 49.2726341,
                        "lng" : -123.1358556
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eJohnston St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ggvkHvqpnVKRgA~AEDS\\W\\KLCJWNs@dAA@A@KLcArA"
                     },
                     "start_location" : {
                        "lat" : 49.27108,
                        "lng" : -123.1338849
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "17 m",
                        "value" : 17
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 49.2727628,
                        "lng" : -123.1357365
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}pvkHb~pnVIGCECCEEA?"
                     },
                     "start_location" : {
                        "lat" : 49.2726341,
                        "lng" : -123.1358556
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 49.2408612,
                        "lng" : -123.1066756
                     },
                     "step_index" : 6,
                     "step_interpolation" : 0.7426533256537704
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "a}nkHxljnV?a@qA@cBB@aCwDDoEFmB?_FIuDI_AAQOkEK{C@WFU?yCI_HMsPWjBBAbCAtDEpIEjBIJAFHN@??rDFtA\\dAHTIH}AjBq@x@NRj@rAnBbFp@bBFI@A?@Xr@BBHEPMB?B?~@kAXQbAITDT@x@?FCn@o@p@s@POF?VJZ]n@w@h@m@fD}DvBgCVa@Rg@T{@Jw@BoBsIMcMSE?@LAVG`@EHERkBzBcCrCoCdD[\\q@bAg@dAe@nAm@|BI`@I`@]AiEAw@CoDKkCEeAAcV[oEI_EMiDAqBCsEKg@AmAA?`B?vACrGEbFmBCkAAyGGiCEqBAyAAuAIyAEAtBC|BIhBK`AA\\GnHGdSElAGfLA~I?XIBIHMNQ@o@Cg@CkACY@KPIh@Kf@OPo@l@g@^Qh@CV?RHn@P`A[Ce@HIDORM^Gd@Bz@LtAFh@a@?e@?O@IHERAjBCjBGPKNIPAN@PJR`@v@Df@Gt@@z@BFFF|@AT`@Zl@HVF\\BRHd@EZI^Uf@qAdAENCv@Id@s@x@KTGd@EfAKf@Wf@EXQpBETKROJQRILKH]HWFQLQNMLMTYa@QY[a@kCqDkBoCKRmAdBk@z@OXWNs@dACBoA`BMMKI"
         },
         "summary" : "Main St",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
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
