[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

Dataset:simple, pts: 50
4 hidden layer size
LR: 0.05
Epoch:500

___________________________________
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 37.37468959698659, correct: 24
Epoch: 20/500, loss: 36.06281606339786, correct: 24
Epoch: 30/500, loss: 35.23199000196706, correct: 24
Epoch: 40/500, loss: 34.78441193496395, correct: 24
Epoch: 50/500, loss: 34.53269211226798, correct: 24
Epoch: 60/500, loss: 34.31131067095132, correct: 24
Epoch: 70/500, loss: 34.013771140049094, correct: 31
Epoch: 80/500, loss: 33.64524564236155, correct: 31
Epoch: 90/500, loss: 33.29750272919236, correct: 31
Epoch: 100/500, loss: 32.851016431415744, correct: 35
Epoch: 110/500, loss: 32.44184489032158, correct: 36
Epoch: 120/500, loss: 31.988255460515205, correct: 37
Epoch: 130/500, loss: 31.400071083782304, correct: 36
Epoch: 140/500, loss: 30.72593492313498, correct: 36
Epoch: 150/500, loss: 29.903454595278337, correct: 37
Epoch: 160/500, loss: 28.99084100449025, correct: 38
Epoch: 170/500, loss: 27.998269580906513, correct: 38
Epoch: 180/500, loss: 26.942618841041867, correct: 41
Epoch: 190/500, loss: 25.809209865859405, correct: 42
Epoch: 200/500, loss: 24.636645701505774, correct: 42
Epoch: 210/500, loss: 23.402756259187186, correct: 43
Epoch: 220/500, loss: 22.142598033028417, correct: 43
Epoch: 230/500, loss: 20.914423299986847, correct: 43
Epoch: 240/500, loss: 19.73917332413353, correct: 44
Epoch: 250/500, loss: 18.60556461839824, correct: 44
Epoch: 260/500, loss: 17.507813870516582, correct: 44
Epoch: 270/500, loss: 16.457764117834337, correct: 44
Epoch: 280/500, loss: 15.474265494727284, correct: 44
Epoch: 290/500, loss: 14.567019980169523, correct: 45
Epoch: 300/500, loss: 13.738192306151129, correct: 46
Epoch: 310/500, loss: 12.985204226363777, correct: 47
Epoch: 320/500, loss: 12.306769169348971, correct: 47
Epoch: 330/500, loss: 11.698532297270615, correct: 47
Epoch: 340/500, loss: 11.150670773865684, correct: 47
Epoch: 350/500, loss: 10.657255424077409, correct: 47
Epoch: 360/500, loss: 10.219995868580197, correct: 48
Epoch: 370/500, loss: 9.832663218114408, correct: 48
Epoch: 380/500, loss: 9.483328790064006, correct: 48
Epoch: 390/500, loss: 9.168424921694488, correct: 48
Epoch: 400/500, loss: 8.881447634696249, correct: 48
Epoch: 410/500, loss: 8.618695964736585, correct: 48
Epoch: 420/500, loss: 8.377396225233417, correct: 48
Epoch: 430/500, loss: 8.15587340061035, correct: 49
Epoch: 440/500, loss: 7.951271785267074, correct: 49
Epoch: 450/500, loss: 7.761583417935309, correct: 49
Epoch: 460/500, loss: 7.585681266947204, correct: 49
Epoch: 470/500, loss: 7.423283271776941, correct: 49
Epoch: 480/500, loss: 7.2721944302946575, correct: 49
Epoch: 490/500, loss: 7.130799734579428, correct: 49
Epoch: 500/500, loss: 6.998125868502954, correct: 49


Dataset:diag, pts: 50
5 hidden layer size
LR: 0.1
Epoch:750

___________________________________
Epoch: 0/775, loss: 0, correct: 0
Epoch: 10/775, loss: 9.984211110040462, correct: 47
Epoch: 20/775, loss: 8.2661060118692, correct: 47
Epoch: 30/775, loss: 7.908015466803921, correct: 47
Epoch: 40/775, loss: 7.729911976153571, correct: 47
Epoch: 50/775, loss: 7.579002331894364, correct: 47
Epoch: 60/775, loss: 7.429081196575819, correct: 47
Epoch: 70/775, loss: 7.27509078672734, correct: 47
Epoch: 80/775, loss: 7.11600813526247, correct: 47
Epoch: 90/775, loss: 6.951648025568768, correct: 47
Epoch: 100/775, loss: 6.78204365025808, correct: 47
Epoch: 110/775, loss: 6.607336944536223, correct: 47
Epoch: 120/775, loss: 6.427770389583022, correct: 47
Epoch: 130/775, loss: 6.243697009923407, correct: 47
Epoch: 140/775, loss: 6.05559071258856, correct: 47
Epoch: 150/775, loss: 5.905914874965872, correct: 47
Epoch: 160/775, loss: 5.769694374964365, correct: 47
Epoch: 170/775, loss: 5.638460531635564, correct: 47
Epoch: 180/775, loss: 5.508745441973178, correct: 47
Epoch: 190/775, loss: 5.379550379332986, correct: 47
Epoch: 200/775, loss: 5.2507437036718265, correct: 47
Epoch: 210/775, loss: 5.122374413013, correct: 47
Epoch: 220/775, loss: 4.994535628444259, correct: 47
Epoch: 230/775, loss: 4.867337597648097, correct: 47
Epoch: 240/775, loss: 4.7409021276314345, correct: 47
Epoch: 250/775, loss: 4.6153608326678714, correct: 47
Epoch: 260/775, loss: 4.490853777623134, correct: 47
Epoch: 270/775, loss: 4.367527913334689, correct: 47
Epoch: 280/775, loss: 4.245535244522707, correct: 48
Epoch: 290/775, loss: 4.125030773876418, correct: 48
Epoch: 300/775, loss: 4.006170287805311, correct: 48
Epoch: 310/775, loss: 3.8891080565809446, correct: 48
Epoch: 320/775, loss: 3.7739945248407665, correct: 48
Epoch: 330/775, loss: 3.6609740684462007, correct: 48
Epoch: 340/775, loss: 3.550182890087976, correct: 48
Epoch: 350/775, loss: 3.443745024280653, correct: 48
Epoch: 360/775, loss: 3.3533422131883, correct: 48
Epoch: 370/775, loss: 3.2649015127339616, correct: 48
Epoch: 380/775, loss: 3.1782848296401736, correct: 48
Epoch: 390/775, loss: 3.09355630030759, correct: 48
Epoch: 400/775, loss: 3.0107864450271076, correct: 48
Epoch: 410/775, loss: 2.930034292567277, correct: 49
Epoch: 420/775, loss: 2.8513465675163703, correct: 49
Epoch: 430/775, loss: 2.7747581443076053, correct: 49
Epoch: 440/775, loss: 2.7002925726014606, correct: 49
Epoch: 450/775, loss: 2.627962678351965, correct: 49
Epoch: 460/775, loss: 2.5577712594760302, correct: 50
Epoch: 470/775, loss: 2.489711863716222, correct: 50
Epoch: 480/775, loss: 2.423769624823376, correct: 50
Epoch: 490/775, loss: 2.3599221316140695, correct: 50
Epoch: 500/775, loss: 2.2981403065023116, correct: 50
Epoch: 510/775, loss: 2.238389273392805, correct: 50
Epoch: 520/775, loss: 2.1806291984651844, correct: 50
Epoch: 530/775, loss: 2.1248160909883493, correct: 50
Epoch: 540/775, loss: 2.070902554680979, correct: 50
Epoch: 550/775, loss: 2.0188384831663777, correct: 50
Epoch: 560/775, loss: 1.9700619480987651, correct: 50
Epoch: 570/775, loss: 1.9232594976624933, correct: 50
Epoch: 580/775, loss: 1.8787377636882945, correct: 50
Epoch: 590/775, loss: 1.834940848049022, correct: 50
Epoch: 600/775, loss: 1.7931440091275512, correct: 50
Epoch: 610/775, loss: 1.753720879650795, correct: 50
Epoch: 620/775, loss: 1.714165122685448, correct: 50
Epoch: 630/775, loss: 1.6767391374799405, correct: 50
Epoch: 640/775, loss: 1.6406839506187965, correct: 50
Epoch: 650/775, loss: 1.6057739212835824, correct: 50
Epoch: 660/775, loss: 1.5718128751385174, correct: 50
Epoch: 670/775, loss: 1.5375327752804535, correct: 50
Epoch: 680/775, loss: 1.50648296274476, correct: 50
Epoch: 690/775, loss: 1.4743546293707241, correct: 50
Epoch: 700/775, loss: 1.4450544102756484, correct: 50
Epoch: 710/775, loss: 1.4154668207438197, correct: 50
Epoch: 720/775, loss: 1.3865592683456112, correct: 50
Epoch: 730/775, loss: 1.3598522100345871, correct: 50
Epoch: 740/775, loss: 1.3325421170165963, correct: 50
Epoch: 750/775, loss: 1.3063522371678902, correct: 50
Epoch: 760/775, loss: 1.281882796022237, correct: 50
Epoch: 770/775, loss: 1.2565746020351156, correct: 50
Epoch: 775/775, loss: 1.2447136878973841, correct: 50

Dataset:split, pts: 50
6 hidden layer size
LR: 0.1
Epoch:750
_____________________________
Epoch: 0/775, loss: 0, correct: 0
Epoch: 10/775, loss: 33.50857357084479, correct: 33
Epoch: 20/775, loss: 32.50768207983357, correct: 33
Epoch: 30/775, loss: 32.19855257724096, correct: 33
Epoch: 40/775, loss: 32.03528806279584, correct: 33
Epoch: 50/775, loss: 31.893676568950422, correct: 33
Epoch: 60/775, loss: 31.758419195027173, correct: 33
Epoch: 70/775, loss: 31.632463131824984, correct: 33
Epoch: 80/775, loss: 31.50782962489067, correct: 33
Epoch: 90/775, loss: 31.38285471053837, correct: 33
Epoch: 100/775, loss: 31.25444005886913, correct: 33
Epoch: 110/775, loss: 31.12356365053729, correct: 33
Epoch: 120/775, loss: 30.98633561219551, correct: 33
Epoch: 130/775, loss: 30.841975401062257, correct: 33
Epoch: 140/775, loss: 30.68882153298857, correct: 33
Epoch: 150/775, loss: 30.524720974634995, correct: 33
Epoch: 160/775, loss: 30.346076481920658, correct: 33
Epoch: 170/775, loss: 30.15148566981335, correct: 33
Epoch: 180/775, loss: 29.93790413248604, correct: 33
Epoch: 190/775, loss: 29.70451004292426, correct: 33
Epoch: 200/775, loss: 29.445437618345963, correct: 34
Epoch: 210/775, loss: 29.157148663086332, correct: 34
Epoch: 220/775, loss: 28.83471990191709, correct: 35
Epoch: 230/775, loss: 28.47217802773962, correct: 36
Epoch: 240/775, loss: 28.063743009034933, correct: 36
Epoch: 250/775, loss: 27.60291204270538, correct: 36
Epoch: 260/775, loss: 27.08458756449086, correct: 36
Epoch: 270/775, loss: 26.501194806068977, correct: 36
Epoch: 280/775, loss: 25.844609745580453, correct: 36
Epoch: 290/775, loss: 25.109231680119514, correct: 36
Epoch: 300/775, loss: 24.290791897951493, correct: 36
Epoch: 310/775, loss: 23.423044259751073, correct: 40
Epoch: 320/775, loss: 22.52477729820921, correct: 40
Epoch: 330/775, loss: 21.584809816448733, correct: 42
Epoch: 340/775, loss: 20.601214875838984, correct: 45
Epoch: 350/775, loss: 19.586645918576068, correct: 47
Epoch: 360/775, loss: 18.5549482310799, correct: 48
Epoch: 370/775, loss: 17.533382675278546, correct: 48
Epoch: 380/775, loss: 16.52435462605199, correct: 48
Epoch: 390/775, loss: 15.53739756099418, correct: 48
Epoch: 400/775, loss: 14.59359158783973, correct: 49
Epoch: 410/775, loss: 13.701616769415983, correct: 49
Epoch: 420/775, loss: 12.874387033418005, correct: 49
Epoch: 430/775, loss: 12.107537314708907, correct: 49
Epoch: 440/775, loss: 11.398455539734991, correct: 49
Epoch: 450/775, loss: 10.748054952619086, correct: 49
Epoch: 460/775, loss: 10.152487871974168, correct: 49
Epoch: 470/775, loss: 9.611835976817256, correct: 49
Epoch: 480/775, loss: 9.121476185043436, correct: 49
Epoch: 490/775, loss: 8.67434353632011, correct: 49
Epoch: 500/775, loss: 8.266762087554543, correct: 49
Epoch: 510/775, loss: 7.897902132223576, correct: 49
Epoch: 520/775, loss: 7.565000002596016, correct: 49
Epoch: 530/775, loss: 7.260616754660321, correct: 49
Epoch: 540/775, loss: 6.983392233871537, correct: 49
Epoch: 550/775, loss: 6.728220586457178, correct: 49
Epoch: 560/775, loss: 6.49289687628739, correct: 49
Epoch: 570/775, loss: 6.275489618479588, correct: 49
Epoch: 580/775, loss: 6.0742986807385515, correct: 49
Epoch: 590/775, loss: 5.888034564700381, correct: 49
Epoch: 600/775, loss: 5.716103505641887, correct: 49
Epoch: 610/775, loss: 5.555855750204822, correct: 49
Epoch: 620/775, loss: 5.406459575808776, correct: 49
Epoch: 630/775, loss: 5.2674745416608735, correct: 49
Epoch: 640/775, loss: 5.137078480576137, correct: 49
Epoch: 650/775, loss: 5.014530166907333, correct: 49
Epoch: 660/775, loss: 4.899167025517264, correct: 49
Epoch: 670/775, loss: 4.790674113064186, correct: 49
Epoch: 680/775, loss: 4.688574565536973, correct: 49
Epoch: 690/775, loss: 4.591899501774073, correct: 49
Epoch: 700/775, loss: 4.500221408408081, correct: 49
Epoch: 710/775, loss: 4.413441726570387, correct: 49
Epoch: 720/775, loss: 4.331220146188551, correct: 49
Epoch: 730/775, loss: 4.252860761125806, correct: 49
Epoch: 740/775, loss: 4.1782497750201415, correct: 49
Epoch: 750/775, loss: 4.10720030946304, correct: 49
Epoch: 760/775, loss: 4.039213162964695, correct: 49
Epoch: 770/775, loss: 3.9740638774087462, correct: 49
Epoch: 775/775, loss: 3.9424894299907303, correct: 49

Dataset:Xor, pts: 50
10 hidden layer size
LR: 0.5
Epoch:750
_____________________________

Epoch: 0/775, loss: 0, correct: 0
Epoch: 10/775, loss: 33.51697526959438, correct: 27
Epoch: 20/775, loss: 32.693526328849025, correct: 36
Epoch: 30/775, loss: 31.692891075490458, correct: 44
Epoch: 40/775, loss: 30.71872358861824, correct: 38
Epoch: 50/775, loss: 32.302463978587795, correct: 30
Epoch: 60/775, loss: 26.31005210594927, correct: 44
Epoch: 70/775, loss: 26.509785204174232, correct: 42
Epoch: 80/775, loss: 22.774682397920817, correct: 44
Epoch: 90/775, loss: 21.859819855616728, correct: 40
Epoch: 100/775, loss: 25.264571590295628, correct: 40
Epoch: 110/775, loss: 20.24633243661728, correct: 44
Epoch: 120/775, loss: 11.654414014579888, correct: 48
Epoch: 130/775, loss: 14.046040230037034, correct: 46
Epoch: 140/775, loss: 10.870620086536444, correct: 48
Epoch: 150/775, loss: 10.751416581496605, correct: 48
Epoch: 160/775, loss: 9.64366124586152, correct: 48
Epoch: 170/775, loss: 8.84618482186054, correct: 48
Epoch: 180/775, loss: 9.613022476165776, correct: 48
Epoch: 190/775, loss: 6.449031168917793, correct: 49
Epoch: 200/775, loss: 13.686734040864993, correct: 44
Epoch: 210/775, loss: 4.432242021554862, correct: 49
Epoch: 220/775, loss: 5.053477583565392, correct: 49
Epoch: 230/775, loss: 15.422604370346157, correct: 43
Epoch: 240/775, loss: 3.495167685375002, correct: 50
Epoch: 250/775, loss: 3.263952250872114, correct: 50
Epoch: 260/775, loss: 4.259199305069471, correct: 49
Epoch: 270/775, loss: 3.7261982853605913, correct: 49
Epoch: 280/775, loss: 2.840136002192881, correct: 50
Epoch: 290/775, loss: 4.208825812249177, correct: 49
Epoch: 300/775, loss: 2.6182305368871908, correct: 49
Epoch: 310/775, loss: 2.538812463537289, correct: 49
Epoch: 320/775, loss: 3.1085929648846538, correct: 49
Epoch: 330/775, loss: 2.7215461221566124, correct: 49
Epoch: 340/775, loss: 1.8850973188707967, correct: 50
Epoch: 350/775, loss: 1.8949123983474443, correct: 50
Epoch: 360/775, loss: 1.9328549959364747, correct: 50
Epoch: 370/775, loss: 2.0004739623220087, correct: 49
Epoch: 380/775, loss: 1.9785814076382873, correct: 49
Epoch: 390/775, loss: 1.8208689501007331, correct: 49
Epoch: 400/775, loss: 1.4172554329550804, correct: 50
Epoch: 410/775, loss: 1.1898372237806687, correct: 50
Epoch: 420/775, loss: 1.0746428384086988, correct: 50
Epoch: 430/775, loss: 1.0384184885909327, correct: 50
Epoch: 440/775, loss: 1.0727221980864599, correct: 50
Epoch: 450/775, loss: 1.0450841486669014, correct: 50
Epoch: 460/775, loss: 1.0172483800577066, correct: 50
Epoch: 470/775, loss: 0.9876386621184053, correct: 50
Epoch: 480/775, loss: 0.9178646140882919, correct: 50
Epoch: 490/775, loss: 0.8733559320061713, correct: 50
Epoch: 500/775, loss: 0.8480267432122546, correct: 50
Epoch: 510/775, loss: 0.7973293579797502, correct: 50
Epoch: 520/775, loss: 0.7303533861481329, correct: 50
Epoch: 530/775, loss: 0.6670333009189886, correct: 50
Epoch: 540/775, loss: 0.663250146852948, correct: 50
Epoch: 550/775, loss: 0.6414973017051816, correct: 50
Epoch: 560/775, loss: 0.6311065284267434, correct: 50
Epoch: 570/775, loss: 0.6316246264352737, correct: 50
Epoch: 580/775, loss: 0.5955235616139283, correct: 50
Epoch: 590/775, loss: 0.581556039873902, correct: 50
Epoch: 600/775, loss: 0.5406177789139225, correct: 50
Epoch: 610/775, loss: 0.5297464547038476, correct: 50
Epoch: 620/775, loss: 0.5412798980808705, correct: 50
Epoch: 630/775, loss: 0.528569990817749, correct: 50
Epoch: 640/775, loss: 0.48748614311794836, correct: 50
Epoch: 650/775, loss: 0.47394971142497166, correct: 50
Epoch: 660/775, loss: 0.464840181234926, correct: 50
Epoch: 670/775, loss: 0.48569846232574443, correct: 50
Epoch: 680/775, loss: 0.44742148901478973, correct: 50
Epoch: 690/775, loss: 0.4303600747574181, correct: 50
Epoch: 700/775, loss: 0.4209890714406436, correct: 50
Epoch: 710/775, loss: 0.42947049841518486, correct: 50
Epoch: 720/775, loss: 0.40188761129952477, correct: 50
Epoch: 730/775, loss: 0.39931330787278524, correct: 50
Epoch: 740/775, loss: 0.3953493572144223, correct: 50
Epoch: 750/775, loss: 0.376414484359484, correct: 50
Epoch: 760/775, loss: 0.3784879056568485, correct: 50
Epoch: 770/775, loss: 0.3610879874943853, correct: 50
Epoch: 775/775, loss: 0.3580954471361914, correct: 50

