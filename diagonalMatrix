public class diagonalMatrix {
	
	/**
	 * Diagonal Matrix Printer
	 * 
	 * This Algorithm was made to properly check a diagonal of a Matrix
	 */
	
	
	public static void main(String[] args) {

		int size = 10; // Grid Size (matrix)
		
		String grid[][] = new String[size][size];
		
		/**
		 * Sample:
		 * Each position for 10 x 10 multidimensional array (Matrix)
		
				{ "00", "01", "02", "03", "04", "05", "06", "07", "08", "09" }
				{ "10", "11", "12", "13", "14", "15", "16", "17", "18", "19" }
				{ "20", "21", "22", "23", "24", "25", "26", "27", "28", "29" }
				{ "30", "31", "32", "33", "34", "35", "36", "37", "38", "39" }
				{ "40", "41", "42", "43", "44", "45", "46", "47", "48", "49" }
				{ "50", "51", "52", "53", "54", "55", "56", "57", "58", "59" }
				{ "60", "61", "62", "63", "64", "65", "66", "67", "68", "69" }
				{ "70", "71", "72", "73", "74", "75", "76", "77", "78", "79" }
				{ "80", "81", "82", "83", "84", "85", "86", "87", "88", "89" }
				{ "90", "91", "92", "93", "94", "95", "96", "97", "98", "99" }
				
		 */
		
		int rowCount = grid.length;
		int columnCount = grid.length;

		// Printing from the Top left to the right
		for (int r = 0; r < rowCount; r++) {
			for (int row = r, col = 0; row >= 0 && col < columnCount; row--, col++) {
			//	System.out.print(grid[row][col] + " ");
				System.out.print(row + "" + col + " ");
			}
			System.out.println();
		}

		// Printing from the bottom left to the right
		for (int c = 0; c <= columnCount; c++) {
			for (int row = rowCount - 1, col = c + 1; row >= 0 && col <= columnCount - 1; row--, col++) {
				System.out.print(row + "" + col + " ");
			}
			System.out.println();
		}

		// Printing from the top right to the left
		for (int r = 0; r < rowCount; r++) {
			for (int row = r, col = columnCount - 1; row >= 0 && col < columnCount; row--, col--) {
				System.out.print(row + "" + col + " ");
			}
			System.out.println();
		}

		// Printing from the bottom right to the left
		for (int c = columnCount - 1; c >= 0; c--) {
			for (int row = rowCount - 1, col = c - 1; row >= 0 && col >= 0; row--, col--) {
				System.out.print(row + "" + col + " ");
			}
			System.out.println();
		}
	}
}
