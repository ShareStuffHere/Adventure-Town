package town;

import java.util.ArrayList;

public class Town {
	//CONSTANTS
	private final int STARTING_SAFETY_RATING = 70;
	
	//Town Fields
	private int mSafetyRating;
	private ArrayList<Building> mBuildings;
	
	public Town()
	{
		this.mSafetyRating = STARTING_SAFETY_RATING;
		this.mBuildings = new ArrayList<Building>();
		
		//All Towns must have at least 1 Center		
		mBuildings.add(new Center());
	}
	
	public int getSafetyRating() {
		return mSafetyRating;
	}

}
