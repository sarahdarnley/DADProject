Our model was too large to run on github. Using VSCode, our outputs were:

**Linear Program:**
Set parameter Username
Set parameter LicenseID to value 2782936
Academic license - for non-commercial use only - expires 2027-02-24
Gurobi Optimizer version 13.0.1 build v13.0.1rc0 (win64 - Windows 11+.0 (26200.2))

CPU model: Intel(R) Core(TM) Ultra 7 155U, instruction set [SSE2|AVX|AVX2]
Thread count: 12 physical cores, 14 logical processors, using up to 14 threads

Optimize a model with 3785 rows, 1585 columns and 10360 nonzeros (Min)
Model fingerprint: 0x5bc357fb
Model has 1010 linear objective coefficients
Model has 25 quadratic objective terms
Variable types: 0 continuous, 1585 integer (1560 binary)
Coefficient statistics:
  Matrix range     [1e+00, 1e+00]
  Objective range  [1e+00, 1e+02]
  QObjective range [4e+01, 4e+01]
  Bounds range     [1e+00, 1e+00]
  RHS range        [1e+00, 4e+01]

Presolve removed 3476 rows and 1062 columns
Presolve time: 0.01s
Presolved: 309 rows, 523 columns, 2044 nonzeros
Presolved model has 24 quadratic objective terms
Variable types: 0 continuous, 523 integer (499 binary)

Root relaxation: objective 5.880625e+02, 391 iterations, 0.00 seconds (0.00 work units)

    Nodes    |    Current Node    |     Objective Bounds      |     Work
 Expl Unexpl |  Obj  Depth IntInf | Incumbent    BestBd   Gap | It/Node Time

     0     0  588.06250    0   42          -  588.06250      -     -    0s
H    0     0                     698.0000000  588.06250  15.8%     -    0s
H    0     0                     600.0000000  588.06250  1.99%     -    0s
     0     0  590.32292    0   28  600.00000  590.32292  1.61%     -    0s
     0     0  591.34062    0   26  600.00000  591.34062  1.44%     -    0s
     0     0  595.77500    0   26  600.00000  595.77500  0.70%     -    0s
     0     0  595.77500    0   14  600.00000  595.77500  0.70%     -    0s
     0     0  598.98750    0    7  600.00000  598.98750  0.17%     -    0s
     0     0  598.98750    0    7  600.00000  598.98750  0.17%     -    0s
     0     0 infeasible    0       600.00000  600.00000  0.00%     -    0s

Explored 1 nodes (1023 simplex iterations) in 0.16 seconds (0.02 work units)
Thread count was 14 (of 14 available processors)

Solution count 2: 600 698 

Optimal solution found (tolerance 1.00e-04)
Best objective 6.000000000000e+02, best bound 6.000000000000e+02, gap 0.0000%
Trip            | Lead Guide      (Rank) | Asst Guide      (Rank)
-----------------------------------------------------------------
Full Moon Paddle & Stargazing at Lake Wauburg1 | jackson o'neill ( 8) | elizabeth driscoll ( 5)
Intro to Backpacking: Providence Canyon1 | alex kuhn       ( 2) | lucy pellenbarg ( 1)
Honors: Canoe & Camp Wekiva Springs | faith franck    ( 1) | sydnie grubba   ( 1)
Intro to Mountain Biking at Santos | jackson o'neill ( 6) | lindsey carpenter ( 7)
Birdwatching & Stargazing Kissimee Prairie Preserve | tomas duque     ( 5) | aleida wells    ( 1)
Canoe with Manatees on the Chassahowitzka | colby dernis    ( 2) | lucy pellenbarg ( 5)
Sea Kayak & Explore Cedar Key1 | NONE            ( 0) | katie wiklund   ( 3)
Beaches & Ponies at Cumberland Island, GA | heidi weiksnar  ( 2) | jordan campbell ( 2)
Intro to Surfing: St. Augustine1 | faith franck    ( 2) | lindsey carpenter ( 2)
Kayak with Manatees on Silver River  | emilia fiebel   ( 4) | luna hernandez  ( 7)
Full Moon Paddle & Stargazing at Lake Wauburg2 | colby dernis    ( 6) | tyler white     ( 4)
Intro to Backpacking: Providence Canyon2 | finnigan smith  (13) | luna hernandez  ( 2)
Canoe & Camp the Suwannee | tomas duque     ( 1) | colby dernis    ( 1)
Honors: Cave Exploring in the Withlacoochee Forest | faith franck    ( 3) | matthew hill    ( 2)
Sea Kayak & Explore Cedar Key2 | NONE            ( 0) | gabriela carvajal ( 2)
Backpack the Pinhoti Trail | francesca orezzoli ( 3) | emilia fiebel   ( 1)
Intro to Surfing: St. Augustine2 | finnigan smith  ( 1) | desi roch-hernandez ( 2)
Honors: Intro to Mountain Biking at Santos | jackson o'neill ( 1) | valeria gutierrez ( 1)
Full Moon Paddle & Stargazing at Lake Wauburg3 | finnigan smith  ( 8) | elizabeth driscoll ( 2)
Backpackin' & Waterfallin' Black Balsam | heidi weiksnar  ( 3) | valeria gutierrez ( 2)
Snorkel Devil's Den & Blue Springs | aleida wells    ( 8) | tyler white     ( 3)
Cave Exploring in the Withlacoochee Forest | benjamin greeno (13) | matthew hill    ( 3)
Hike & Help Linville Gorge | francesca orezzoli ( 7) | gabriela carvajal ( 1)
OCL Devil's Den TRiP | sydnie grubba   ( 6) | pablo sanchez   (10)
Sunset Surf & Explore St Augustine | elizabeth driscoll ( 3) | desi roch-hernandez ( 3)
Sea Kayak & Explore Cedar Key3 | NONE            ( 0) | jordan campbell ( 6)
Backpack & Summit Mt Mitchell | alex kuhn       ( 1) | pablo sanchez   ( 6)
Intro to Surfing: St. Augustine3 | heidi weiksnar  ( 8) | katie wiklund   ( 4)
SUP & Snorkel Rainbow River | benjamin greeno ( 3) | amber ni        ( 4)
Honors: Tube the Itchetucknee River | emilia fiebel   ( 5) | amber ni        ( 2)
------------------------------
Total Rank Sum (Satisfaction): 220
------------------------------
Staff Member    | Assigned Trips                           | Total Rank
---------------------------------------------------------------------------
jordan campbell | Beaches & Ponies at Cumberland Island, GA (Asst), Sea Kayak & Explore Cedar Key3 (Asst) | 8
jackson o'neill | Full Moon Paddle & Stargazing at Lake Wauburg1 (Lead), Intro to Mountain Biking at Santos (Lead), Honors: Intro to Mountain Biking at Santos (Lead) | 15
lindsey carpenter | Intro to Mountain Biking at Santos (Asst), Intro to Surfing: St. Augustine1 (Asst) | 9
desi roch-hernandez | Intro to Surfing: St. Augustine2 (Asst), Sunset Surf & Explore St Augustine (Asst) | 5
faith franck    | Honors: Canoe & Camp Wekiva Springs (Lead), Intro to Surfing: St. Augustine1 (Lead), Honors: Cave Exploring in the Withlacoochee Forest (Lead) | 6
valeria gutierrez | Honors: Intro to Mountain Biking at Santos (Asst), Backpackin' & Waterfallin' Black Balsam (Asst) | 3
lucy pellenbarg | Intro to Backpacking: Providence Canyon1 (Asst), Canoe with Manatees on the Chassahowitzka (Asst) | 6
tomas duque     | Birdwatching & Stargazing Kissimee Prairie Preserve (Lead), Canoe & Camp the Suwannee (Lead) | 6
finnigan smith  | Intro to Backpacking: Providence Canyon2 (Lead), Intro to Surfing: St. Augustine2 (Lead), Full Moon Paddle & Stargazing at Lake Wauburg3 (Lead) | 22
pablo sanchez   | OCL Devil's Den TRiP (Asst), Backpack & Summit Mt Mitchell (Asst) | 16
luna hernandez  | Kayak with Manatees on Silver River  (Asst), Intro to Backpacking: Providence Canyon2 (Asst) | 9
tyler white     | Full Moon Paddle & Stargazing at Lake Wauburg2 (Asst), Snorkel Devil's Den & Blue Springs (Asst) | 7
katie wiklund   | Sea Kayak & Explore Cedar Key1 (Asst), Intro to Surfing: St. Augustine3 (Asst) | 7
alex kuhn       | Intro to Backpacking: Providence Canyon1 (Lead), Backpack & Summit Mt Mitchell (Lead) | 3
heidi weiksnar  | Beaches & Ponies at Cumberland Island, GA (Lead), Backpackin' & Waterfallin' Black Balsam (Lead), Intro to Surfing: St. Augustine3 (Lead) | 13
amber ni        | SUP & Snorkel Rainbow River (Asst), Honors: Tube the Itchetucknee River (Asst) | 6
benjamin greeno | Cave Exploring in the Withlacoochee Forest (Lead), SUP & Snorkel Rainbow River (Lead) | 16
emilia fiebel   | Kayak with Manatees on Silver River  (Lead), Honors: Tube the Itchetucknee River (Lead), Backpack the Pinhoti Trail (Asst) | 10
colby dernis    | Canoe with Manatees on the Chassahowitzka (Lead), Full Moon Paddle & Stargazing at Lake Wauburg2 (Lead), Canoe & Camp the Suwannee (Asst) | 9
matthew hill    | Honors: Cave Exploring in the Withlacoochee Forest (Asst), Cave Exploring in the Withlacoochee Forest (Asst) | 5
sydnie grubba   | OCL Devil's Den TRiP (Lead), Honors: Canoe & Camp Wekiva Springs (Asst) | 7
aleida wells    | Snorkel Devil's Den & Blue Springs (Lead), Birdwatching & Stargazing Kissimee Prairie Preserve (Asst) | 9
francesca orezzoli | Backpack the Pinhoti Trail (Lead), Hike & Help Linville Gorge (Lead) | 10
gabriela carvajal | Sea Kayak & Explore Cedar Key2 (Asst), Hike & Help Linville Gorge (Asst) | 3
elizabeth driscoll | Sunset Surf & Explore St Augustine (Lead), Full Moon Paddle & Stargazing at Lake Wauburg1 (Asst), Full Moon Paddle & Stargazing at Lake Wauburg3 (Asst) | 10

**Weighted Model:**
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: gurobipy in C:\Users\sarah\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.13_qbz5n2kfra8p0\LocalCache\local-packages\Python313\site-packages (13.0.1)
Set parameter Username
Set parameter LicenseID to value 2782936
Academic license - for non-commercial use only - expires 2027-02-24
Gurobi Optimizer version 13.0.1 build v13.0.1rc0 (win64 - Windows 11+.0 (26200.2))

CPU model: Intel(R) Core(TM) Ultra 7 155U, instruction set [SSE2|AVX|AVX2]
Thread count: 12 physical cores, 14 logical processors, using up to 14 threads

Optimize a model with 3787 rows, 1585 columns and 10420 nonzeros (Min)
Model fingerprint: 0xb1b5b7e1
Model has 1010 linear objective coefficients
Model has 25 quadratic objective terms
Variable types: 0 continuous, 1585 integer (1560 binary)
Coefficient statistics:
  Matrix range     [1e+00, 1e+00]
  Objective range  [1e+00, 3e+07]
  QObjective range [4e+01, 4e+01]
  Bounds range     [1e+00, 1e+00]
  RHS range        [1e+00, 4e+01]

Presolve removed 3481 rows and 1091 columns
Presolve time: 0.03s
Presolved: 306 rows, 494 columns, 2001 nonzeros
Presolved model has 24 quadratic objective terms
Variable types: 0 continuous, 494 integer (470 binary)

Root relaxation: objective 4.303041e+07, 381 iterations, 0.00 seconds (0.00 work units)

    Nodes    |    Current Node    |     Objective Bounds      |     Work
 Expl Unexpl |  Obj  Depth IntInf | Incumbent    BestBd   Gap | It/Node Time

     0     0 4.3030e+07    0   18          - 4.3030e+07      -     -    0s
H    0     0                    4.303042e+07 4.3030e+07  0.00%     -    0s

Explored 1 nodes (381 simplex iterations) in 0.09 seconds (0.01 work units)
Thread count was 14 (of 14 available processors)

Solution count 1: 4.30304e+07 

Optimal solution found (tolerance 1.00e-04)
Best objective 4.303042397017e+07, best bound 4.303040799503e+07, gap 0.0000%
Trip            | Lead Guide      (Rank) | Asst Guide      (Rank)
-----------------------------------------------------------------
Full Moon Paddle & Stargazing at Lake Wauburg1 | jackson o'neill ( 8) | luna hernandez  (10)
Intro to Backpacking: Providence Canyon1 | alex kuhn       ( 2) | katie wiklund   ( 1)
Honors: Canoe & Camp Wekiva Springs | faith franck    ( 1) | sydnie grubba   ( 1)
Intro to Mountain Biking at Santos | jackson o'neill ( 6) | valeria gutierrez ( 7)
Birdwatching & Stargazing Kissimee Prairie Preserve | tomas duque     ( 5) | aleida wells    ( 1)
Canoe with Manatees on the Chassahowitzka | colby dernis    ( 2) | lucy pellenbarg ( 5)
Sea Kayak & Explore Cedar Key1 | NONE            ( 0) | katie wiklund   ( 3)
Beaches & Ponies at Cumberland Island, GA | heidi weiksnar  ( 2) | luna hernandez  ( 1)
Intro to Surfing: St. Augustine1 | faith franck    ( 2) | lindsey carpenter ( 2)
Kayak with Manatees on Silver River  | emilia fiebel   ( 4) | desi roch-hernandez ( 5)
Full Moon Paddle & Stargazing at Lake Wauburg2 | colby dernis    ( 6) | tyler white     ( 4)
Intro to Backpacking: Providence Canyon2 | faith franck    ( 5) | elizabeth driscoll ( 1)
Canoe & Camp the Suwannee | tomas duque     ( 1) | colby dernis    ( 1)
Honors: Cave Exploring in the Withlacoochee Forest | benjamin greeno (12) | matthew hill    ( 2)
Sea Kayak & Explore Cedar Key2 | NONE            ( 0) | gabriela carvajal ( 2)
Backpack the Pinhoti Trail | francesca orezzoli ( 3) | emilia fiebel   ( 1)
Intro to Surfing: St. Augustine2 | finnigan smith  ( 1) | desi roch-hernandez ( 2)
Honors: Intro to Mountain Biking at Santos | jackson o'neill ( 1) | jordan campbell ( 4)
Full Moon Paddle & Stargazing at Lake Wauburg3 | finnigan smith  ( 8) | pablo sanchez   (12)
Backpackin' & Waterfallin' Black Balsam | francesca orezzoli ( 1) | valeria gutierrez ( 2)
Snorkel Devil's Den & Blue Springs | finnigan smith  ( 3) | tyler white     ( 3)
Cave Exploring in the Withlacoochee Forest | benjamin greeno (13) | matthew hill    ( 3)
Hike & Help Linville Gorge | francesca orezzoli ( 7) | pablo sanchez   ( 1)
OCL Devil's Den TRiP | sydnie grubba   ( 6) | lindsey carpenter (10)
Sunset Surf & Explore St Augustine | elizabeth driscoll ( 3) | desi roch-hernandez ( 3)
Sea Kayak & Explore Cedar Key3 | NONE            ( 0) | jordan campbell ( 6)
Backpack & Summit Mt Mitchell | alex kuhn       ( 1) | gabriela carvajal ( 5)
Intro to Surfing: St. Augustine3 | heidi weiksnar  ( 8) | lucy pellenbarg ( 4)
SUP & Snorkel Rainbow River | benjamin greeno ( 3) | amber ni        ( 4)
Honors: Tube the Itchetucknee River | aleida wells    ( 9) | amber ni        ( 2)
------------------------------
Total Rank Sum (Satisfaction): 231
------------------------------
Staff Member    | Assigned Trips                           | Total Rank
---------------------------------------------------------------------------
jordan campbell | Honors: Intro to Mountain Biking at Santos (Asst), Sea Kayak & Explore Cedar Key3 (Asst) | 10
jackson o'neill | Full Moon Paddle & Stargazing at Lake Wauburg1 (Lead), Intro to Mountain Biking at Santos (Lead), Honors: Intro to Mountain Biking at Santos (Lead) | 15
lindsey carpenter | Intro to Surfing: St. Augustine1 (Asst), OCL Devil's Den TRiP (Asst) | 12
desi roch-hernandez | Kayak with Manatees on Silver River  (Asst), Intro to Surfing: St. Augustine2 (Asst), Sunset Surf & Explore St Augustine (Asst) | 10
faith franck    | Honors: Canoe & Camp Wekiva Springs (Lead), Intro to Surfing: St. Augustine1 (Lead), Intro to Backpacking: Providence Canyon2 (Lead) | 8
valeria gutierrez | Intro to Mountain Biking at Santos (Asst), Backpackin' & Waterfallin' Black Balsam (Asst) | 9
lucy pellenbarg | Canoe with Manatees on the Chassahowitzka (Asst), Intro to Surfing: St. Augustine3 (Asst) | 9
tomas duque     | Birdwatching & Stargazing Kissimee Prairie Preserve (Lead), Canoe & Camp the Suwannee (Lead) | 6
finnigan smith  | Intro to Surfing: St. Augustine2 (Lead), Full Moon Paddle & Stargazing at Lake Wauburg3 (Lead), Snorkel Devil's Den & Blue Springs (Lead) | 12
pablo sanchez   | Full Moon Paddle & Stargazing at Lake Wauburg3 (Asst), Hike & Help Linville Gorge (Asst) | 13
luna hernandez  | Full Moon Paddle & Stargazing at Lake Wauburg1 (Asst), Beaches & Ponies at Cumberland Island, GA (Asst) | 11
tyler white     | Full Moon Paddle & Stargazing at Lake Wauburg2 (Asst), Snorkel Devil's Den & Blue Springs (Asst) | 7
katie wiklund   | Intro to Backpacking: Providence Canyon1 (Asst), Sea Kayak & Explore Cedar Key1 (Asst) | 4
alex kuhn       | Intro to Backpacking: Providence Canyon1 (Lead), Backpack & Summit Mt Mitchell (Lead) | 3
heidi weiksnar  | Beaches & Ponies at Cumberland Island, GA (Lead), Intro to Surfing: St. Augustine3 (Lead) | 10
amber ni        | SUP & Snorkel Rainbow River (Asst), Honors: Tube the Itchetucknee River (Asst) | 6
benjamin greeno | Honors: Cave Exploring in the Withlacoochee Forest (Lead), Cave Exploring in the Withlacoochee Forest (Lead), SUP & Snorkel Rainbow River (Lead) | 28
emilia fiebel   | Kayak with Manatees on Silver River  (Lead), Backpack the Pinhoti Trail (Asst) | 5
colby dernis    | Canoe with Manatees on the Chassahowitzka (Lead), Full Moon Paddle & Stargazing at Lake Wauburg2 (Lead), Canoe & Camp the Suwannee (Asst) | 9
matthew hill    | Honors: Cave Exploring in the Withlacoochee Forest (Asst), Cave Exploring in the Withlacoochee Forest (Asst) | 5
sydnie grubba   | OCL Devil's Den TRiP (Lead), Honors: Canoe & Camp Wekiva Springs (Asst) | 7
aleida wells    | Honors: Tube the Itchetucknee River (Lead), Birdwatching & Stargazing Kissimee Prairie Preserve (Asst) | 10
francesca orezzoli | Backpack the Pinhoti Trail (Lead), Backpackin' & Waterfallin' Black Balsam (Lead), Hike & Help Linville Gorge (Lead) | 11
gabriela carvajal | Sea Kayak & Explore Cedar Key2 (Asst), Backpack & Summit Mt Mitchell (Asst) | 7
elizabeth driscoll | Sunset Surf & Explore St Augustine (Lead), Intro to Backpacking: Providence Canyon2 (Asst) | 4
