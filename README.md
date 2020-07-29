# Linear-Regression-Repository


RESULTs:

cv값을 13으로 설정하고,learning rates(0.1, 0.01, 0.001, 0.0001), L1/L2 그리고 lambda(0, 0.0001, 0.001, 0.01, 0.1, 1.0) 의 모든 조합에서 하이퍼파라미터 튜닝을 진행하였고 아래가 그 결과입니다.


Ave. mse - lerning rate:0.1, regularizer: l1, lambd: 1.0 -> 0.4146626068392543

Ave. mse - lerning rate:0.01, regularizer: l1, lambd: 1.0 -> 0.41456961858483143

Ave. mse - lerning rate:0.001, regularizer: l1, lambd: 1.0 -> 4.878947847004683

Ave. mse - lerning rate:0.0001, regularizer: l1, lambd: 1.0 -> 26.764989903666873

Ave. mse - lerning rate:0.1, regularizer: l1, lambd: 0.1 -> 0.4146219838589052

Ave. mse - lerning rate:0.01, regularizer: l1, lambd: 0.1 -> 0.41454468782388565

Ave. mse - lerning rate:0.001, regularizer: l1, lambd: 0.1 -> 4.880501503805198

Ave. mse - lerning rate:0.0001, regularizer: l1, lambd: 0.1 -> 26.765645472976352

Ave. mse - lerning rate:0.1, regularizer: l1, lambd: 0.01 -> 0.4146186257398737

Ave. mse - lerning rate:0.01, regularizer: l1, lambd: 0.01 -> 0.41454266336365125

Ave. mse - lerning rate:0.001, regularizer: l1, lambd: 0.01 -> 4.880657002897653

Ave. mse - lerning rate:0.0001, regularizer: l1, lambd: 0.01 -> 26.765711034471636

Ave. mse - lerning rate:0.1, regularizer: l1, lambd: 0.001 -> 0.4146182969697607

Ave. mse - lerning rate:0.01, regularizer: l1, lambd: 0.001 -> 0.4145424651326638

Ave. mse - lerning rate:0.001, regularizer: l1, lambd: 0.001 -> 4.88067255414102

Ave. mse - lerning rate:0.0001, regularizer: l1, lambd: 0.001 -> 26.765717590666817

Ave. mse - lerning rate:0.1, regularizer: l1, lambd: 0.0001 -> 0.4146182641631674

Ave. mse - lerning rate:0.01, regularizer: l1, lambd: 0.0001 -> 0.41454244537016105

Ave. mse - lerning rate:0.001, regularizer: l1, lambd: 0.0001 -> 4.880674109278698

Ave. mse - lerning rate:0.0001, regularizer: l1, lambd: 0.0001 -> 26.765718246286795

Ave. mse - lerning rate:0.1, regularizer: l1, lambd: 0 -> 0.41461826051878065

Ave. mse - lerning rate:0.01, regularizer: l1, lambd: 0 -> 0.4145424431747802

Ave. mse - lerning rate:0.001, regularizer: l1, lambd: 0 -> 4.880674282071921

Ave. mse - lerning rate:0.0001, regularizer: l1, lambd: 0 -> 26.76571831913345

Ave. mse - lerning rate:0.1, regularizer: l2, lambd: 1.0 -> 0.41447545931002355

Ave. mse - lerning rate:0.01, regularizer: l2, lambd: 1.0 -> 0.414383921049297

Ave. mse - lerning rate:0.001, regularizer: l2, lambd: 1.0 -> 4.876427948847615

Ave. mse - lerning rate:0.0001, regularizer: l2, lambd: 1.0 -> 26.765535502336284

Ave. mse - lerning rate:0.1, regularizer: l2, lambd: 0.1 -> 0.4146026329952742

Ave. mse - lerning rate:0.01, regularizer: l2, lambd: 0.1 -> 0.41452525924038797

Ave. mse - lerning rate:0.001, regularizer: l2, lambd: 0.1 -> 4.880249635824445

Ave. mse - lerning rate:0.0001, regularizer: l2, lambd: 0.1 -> 26.76570003779279

Ave. mse - lerning rate:0.1, regularizer: l2, lambd: 0.01 -> 0.41461668431160015

Ave. mse - lerning rate:0.01, regularizer: l2, lambd: 0.01 -> 0.4145407114823196

Ave. mse - lerning rate:0.001, regularizer: l2, lambd: 0.01 -> 4.880631817318179

Ave. mse - lerning rate:0.0001, regularizer: l2, lambd: 0.01 -> 26.765716491002777

Ave. mse - lerning rate:0.1, regularizer: l2, lambd: 0.001 -> 0.4146181027635334

Ave. mse - lerning rate:0.01, regularizer: l2, lambd: 0.001 -> 0.41454226987256204

Ave. mse - lerning rate:0.001, regularizer: l2, lambd: 0.001 -> 4.880670035595255

Ave. mse - lerning rate:0.0001, regularizer: l2, lambd: 0.001 -> 26.765718136320423

Ave. mse - lerning rate:0.1, regularizer: l2, lambd: 0.0001 -> 0.41461824474191067

Ave. mse - lerning rate:0.01, regularizer: l2, lambd: 0.0001 -> 0.4145424258432287

Ave. mse - lerning rate:0.001, regularizer: l2, lambd: 0.0001 -> 4.8806738574242505

Ave. mse - lerning rate:0.0001, regularizer: l2, lambd: 0.0001 -> 26.765718300852154

Ave. mse - lerning rate:0.1, regularizer: l2, lambd: 0 -> 0.41461826051878065

Ave. mse - lerning rate:0.01, regularizer: l2, lambd: 0 -> 0.4145424431747802

Ave. mse - lerning rate:0.001, regularizer: l2, lambd: 0 -> 4.880674282071921

Ave. mse - lerning rate:0.0001, regularizer: l2, lambd: 0 -> 26.76571831913345



최적의 하이퍼파라미터 값으로 저희가 찾은 값은:

The Minimal error is:  0.414383921049297

    The best Hyperparameters: 
      lerning rate:0.01, regularizer: l2, lambd: 1.0
      
였고, 이 결과로 evaluation set에 모델을 크로스 벨리데이션 했을때의 MSE는 0.45883545819290306 였습니다.

