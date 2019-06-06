---
scapolite:
    class: collection
    version: '0.51'
    lang: en
    format: md
id: Windows_Server_2016_STIG
id_namespace: mil.disa
version: '001.007'
status: accepted
title: Windows Server 2016 Security Technical Implementation Guide
notice: <see below>
objectives: <see below>
applicability:
  - system: https://scap.nist.gov/schema/cpe/2.3
    cpes:
      - cpe:/o:microsoft:windows_server_2016:-
contents:
  - class: group_ref
    idref: V-73239
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73247
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73271
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73287
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73289
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000096-GPOS-00050
  - class: group_ref
    idref: V-73291
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73293
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73295
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000096-GPOS-00050
  - class: group_ref
    idref: V-73297
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73299
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73301
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73309
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000329-GPOS-00128
  - class: group_ref
    idref: V-73311
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000021-GPOS-00005
  - class: group_ref
    idref: V-73313
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000021-GPOS-00005
  - class: group_ref
    idref: V-73315
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000077-GPOS-00045
  - class: group_ref
    idref: V-73317
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000076-GPOS-00044
  - class: group_ref
    idref: V-73319
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000075-GPOS-00043
  - class: group_ref
    idref: V-73321
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000078-GPOS-00046
  - class: group_ref
    idref: V-73323
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000069-GPOS-00037
  - class: group_ref
    idref: V-73325
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000073-GPOS-00041
  - class: group_ref
    idref: V-73359
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-73361
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-73363
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-73365
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-73367
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000112-GPOS-00057
  - class: group_ref
    idref: V-73369
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73405
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-73407
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-73409
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-73411
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000257-GPOS-00098
  - class: group_ref
    idref: V-73413
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-73415
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-73419
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73423
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000004-GPOS-00004
  - class: group_ref
    idref: V-73427
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000004-GPOS-00004
  - class: group_ref
    idref: V-73429
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000004-GPOS-00004
  - class: group_ref
    idref: V-73433
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73435
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73437
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73439
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73441
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73443
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000240-GPOS-00090
  - class: group_ref
    idref: V-73445
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000240-GPOS-00090
  - class: group_ref
    idref: V-73449
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000032-GPOS-00013
  - class: group_ref
    idref: V-73451
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000032-GPOS-00013
  - class: group_ref
    idref: V-73453
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000032-GPOS-00013
  - class: group_ref
    idref: V-73455
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000470-GPOS-00214
  - class: group_ref
    idref: V-73461
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73463
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73465
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73467
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73469
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73471
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73473
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73475
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73477
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73479
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73481
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73483
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73487
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73489
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73491
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000327-GPOS-00127
  - class: group_ref
    idref: V-73493
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73495
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73497
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73499
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73501
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73503
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73505
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000420-GPOS-00186
  - class: group_ref
    idref: V-73507
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73509
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73511
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000042-GPOS-00020
  - class: group_ref
    idref: V-73521
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73525
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73527
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73529
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73531
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73533
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73537
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73539
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73541
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000379-GPOS-00164
  - class: group_ref
    idref: V-73543
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73545
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000368-GPOS-00154
  - class: group_ref
    idref: V-73547
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000368-GPOS-00154
  - class: group_ref
    idref: V-73549
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000368-GPOS-00154
  - class: group_ref
    idref: V-73551
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73553
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000341-GPOS-00132
  - class: group_ref
    idref: V-73555
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000341-GPOS-00132
  - class: group_ref
    idref: V-73557
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000341-GPOS-00132
  - class: group_ref
    idref: V-73559
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73561
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000433-GPOS-00192
  - class: group_ref
    idref: V-73563
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73565
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73567
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73569
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000138-GPOS-00069
  - class: group_ref
    idref: V-73571
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73573
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000250-GPOS-00093
  - class: group_ref
    idref: V-73575
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000250-GPOS-00093
  - class: group_ref
    idref: V-73577
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73579
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73581
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-73583
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000362-GPOS-00149
  - class: group_ref
    idref: V-73585
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000362-GPOS-00149
  - class: group_ref
    idref: V-73587
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73589
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00229
  - class: group_ref
    idref: V-73591
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000042-GPOS-00020
  - class: group_ref
    idref: V-73593
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000125-GPOS-00065
  - class: group_ref
    idref: V-73595
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000393-GPOS-00173
  - class: group_ref
    idref: V-73597
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000125-GPOS-00065
  - class: group_ref
    idref: V-73599
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000125-GPOS-00065
  - class: group_ref
    idref: V-73601
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000393-GPOS-00173
  - class: group_ref
    idref: V-73603
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73605
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000066-GPOS-00034
  - class: group_ref
    idref: V-73607
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000066-GPOS-00034
  - class: group_ref
    idref: V-73609
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000066-GPOS-00034
  - class: group_ref
    idref: V-73621
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73623
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73625
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73627
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000062-GPOS-00031
  - class: group_ref
    idref: V-73629
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73631
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73633
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73635
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73637
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73639
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000379-GPOS-00164
  - class: group_ref
    idref: V-73641
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73643
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73645
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000029-GPOS-00010
  - class: group_ref
    idref: V-73647
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000023-GPOS-00006
  - class: group_ref
    idref: V-73649
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000023-GPOS-00006
  - class: group_ref
    idref: V-73651
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73653
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73655
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73657
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000074-GPOS-00042
  - class: group_ref
    idref: V-73659
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000163-GPOS-00072
  - class: group_ref
    idref: V-73661
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73663
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000423-GPOS-00187
  - class: group_ref
    idref: V-73667
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73669
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000138-GPOS-00069
  - class: group_ref
    idref: V-73671
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73673
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73675
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000138-GPOS-00069
  - class: group_ref
    idref: V-73677
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73679
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73681
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73683
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73685
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000120-GPOS-00061
  - class: group_ref
    idref: V-73687
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000073-GPOS-00041
  - class: group_ref
    idref: V-73689
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000163-GPOS-00072
  - class: group_ref
    idref: V-73691
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73693
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73695
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73697
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73699
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000067-GPOS-00035
  - class: group_ref
    idref: V-73701
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000033-GPOS-00014
  - class: group_ref
    idref: V-73703
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73705
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73707
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73709
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73711
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73713
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73715
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73717
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73719
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000373-GPOS-00157
  - class: group_ref
    idref: V-73721
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000134-GPOS-00068
  - class: group_ref
    idref: V-73729
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73731
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73733
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73735
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73737
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73739
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73741
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73743
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73745
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73747
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73749
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73751
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73753
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73755
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73757
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73759
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73761
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73763
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73765
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73767
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73769
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73771
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000080-GPOS-00048
  - class: group_ref
    idref: V-73773
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000297-GPOS-00115
  - class: group_ref
    idref: V-73775
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000297-GPOS-00115
  - class: group_ref
    idref: V-73777
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73779
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73781
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73783
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73785
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73787
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73789
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73791
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73793
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000057-GPOS-00027
  - class: group_ref
    idref: V-73795
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73797
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73799
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73801
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73803
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000324-GPOS-00125
  - class: group_ref
    idref: V-73807
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000480-GPOS-00227
  - class: group_ref
    idref: V-73809
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000121-GPOS-000062
  - class: group_ref
    idref: V-78123
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
  - class: group_ref
    idref: V-78125
    idref_namespace: mil.disa.Windows-Server-2016-STIG
    ref_comment: SRG-OS-000095-GPOS-00049
profiles:
  - class: profile_ref
    idref: MAC-1_Classified
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-1_Public
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-1_Sensitive
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-2_Classified
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-2_Public
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-2_Sensitive
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-3_Classified
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-3_Public
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: MAC-3_Sensitive
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: Disable_Slow_Rules
    idref_namespace: mil.disa.Windows-Server-2016-STIG
  - class: profile_ref
    idref: CAT_I_Only
    idref_namespace: mil.disa.Windows-Server-2016-STIG
history:
  - version: '001.007'
    date: '2018-10-26'
    action: created
    short_description: accepted
    internal_comment: ''
---


## /notice


This content has been produced from an import of the

IASE Windows Server 2016 STIG V1R7

SCAP datastream into the Scapolite format.

Please refer to the [slide set about Scapolite](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/grobauer_siemens_scap_v2_experiences_scapolite.pdf)
that has been presented at NIST's SCAP v2 workshop for more information about Scapolite.

The machine-readable information on how to implement the settings
is *not* part of the original IASE DISA STIG; the information
has been added using the mechanisms described in the
[slide set about automating implementation](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/stoeckle_tum_scap_v2_scapolite_automated_implementation.pdf)
that has been presented at NIST's SCAP v2 workshop.

Copyright holder for the contents of the IASE Windows Server 2016 STIG V1R7, is IASE DISA,
please refer to [DoD CyberExchange Website](https://public.cyber.mil/stigs/downloads/) for
information about the STIGs and access to the authoritative versions of the STIGs.
This project merely uses the STIG as an example of how SCAP content can be expressed
and enriched in Scapolite.

For feedback/questions/discussion please use the mailing list

https://list.nist.gov/scap-dev-authoring 


 

 
      

## /objectives

This Security Technical Implementation Guide is published as a tool to improve the security of Department of Defense (DoD) information systems. The requirements are derived from the National Institute of Standards and Technology (NIST) 800-53 and related documents. Comments or proposed revisions to this document should be sent via email to the following address: disa.stig_spt@mail.mil.
