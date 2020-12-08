# Triangle-tree
async function startProgram() {
	// This is our sample code for making the RVR drive in a square.

	await roll(56,50,3.8) //Drive for two seconds at a speed of 50 at a heading of 0 degrees.
	await stopRoll()
	await roll(270,50,5.8)//Continue for each corner of the square
	await stopRoll()
	await roll(136,50,3.8) 
	 //This realigns the robot at the end of the movement.
	
	await roll(0,50,0.5)
	
	
}
