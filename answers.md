Activity 3
---------------

## Questions
1.
	public static String flip() {
		double prob = Math.random();
		if (prob > 0.66) {
			return "tails";
		}
		return "heads";
	}

2.
	public static boolean arePermutations(int[] a, int[] b) {
		int correct = 0;
		for (int i=0; i < a.length; i++) {
			for (int j=0; j < b.length; j++) {
				if (a[j] == b[k]) {
					correct++;
				}
			}
		}
		return (correct == a.length + 1);
	}
3. 0,1,1,0 would reverse the order of the cards