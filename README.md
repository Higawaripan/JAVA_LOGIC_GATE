# JAVA_LOGIC_GATE
JAVAに論理ゲートを...使う機会少ないけど

LC.○○（○○はゲートの名前）で選べるが代入値はブール値です

一覧

    System.out.println(LC.OR(false,true)+"-OR");//OR..ORゲート
		System.out.println(LC.NOT(false)+"-NOT");//NOT..NOTゲート
		System.out.println(LC.AND(true, false)+"-AND");//AND..ANDゲート
		System.out.println(LC.NAND(true, false)+"-NAND");//NAND..NANDゲート
		System.out.println(LC.XOR(true, false)+"-XOR");//XOR..XORゲート
		System.out.println(LC.XNOR(true, false)+"-XNOR");//XNOR..XNORゲート
		System.out.println(LC.BUF(null)+"-BUF");//BUF..nullの場合自動でfalse(エラーを防ぐために)
		System.out.println(LC.Converter(false)+"-Converter(Boolean)");//Coverter..ブール値を数字に(1か0)
		System.out.println(LC.Converter(0)+"-Converter(Int)");//Converter..数字をブール値に(1以上true,未満false)
		System.out.println(LC.OneWayConverter_I(true)+"-OneWayConverter_I");//OneWayConverter_I..値を絶対に数字で
		System.out.println(LC.OneWayConverter_B(true)+"-OneWayConverter_B");//OneWayConverter_B..値を絶対にブール値で
		System.out.println(LC.OneWayConverter_I(1)+"-OneWayConverter_I");
		System.out.println(LC.OneWayConverter_B(1)+"-OneWayConverter_B");
		System.out.println(LC.OneWayConverter_I(true));

if文とかに組み合わせてもいいね！！値はBoolean型で基本帰ってくる、一部Int型

今回のは動画で紹介したプログラムです

