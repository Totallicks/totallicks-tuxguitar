package org.herac.tuxguitar.io.gpx.score;

public class GPXNote {
	
	private int id;
	private int fret;
	private int string;
	private int tone;
	private int octave;
	private int element;
	private int variation;
	private int midiNumber;
	// bends are measured in % of full step.  100 = full step, not 100 (cents) = half step
	private boolean BendEnabled;
	private int BendOriginValue;
	private int BendMiddleValue;
	private int BendDestinationValue;

	private boolean hammer;
	private boolean slide;
	private int SlideFlags;	// 1, 2, 4, 8, 16 - 2 seems to be up, 4 seems to be down.
	private boolean vibrato;
	private boolean Tapped;
	private boolean tieDestination;
	private boolean mutedEnabled;
	private boolean palmMutedEnabled;

	private boolean Harmonic;
	private int HarmonicFret;
	private String HarmonicType;
	
	public GPXNote(){
		super();
		this.id = -1;
		this.fret = -1;
		this.string = -1;
		this.tone = -1;
		this.octave = -1;
		this.element = -1;
		this.variation = -1;
		this.midiNumber = -1;
		this.hammer = false;
		this.BendEnabled = false;
		this.BendOriginValue = 0;
		this.BendMiddleValue = 0;
		this.BendDestinationValue = 0;
		this.SlideFlags = 0;
		this.Harmonic = false;
		this.HarmonicType = "";
		this.HarmonicFret = -1;
	}
	
	public int getId() {
		return this.id;
	}
	
	public void setId(int id) {
		this.id = id;
	}
	
	public int getFret() {
		return this.fret;
	}
	
	public void setFret(int fret) {
		this.fret = fret;
	}
	
	public int getString() {
		return this.string;
	}
	
	public void setString(int string) {
		this.string = string;
	}
	
	public int getTone() {
		return tone;
	}
	
	public void setTone(int tone) {
		this.tone = tone;
	}
	
	public int getOctave() {
		return octave;
	}
	
	public void setOctave(int octave) {
		this.octave = octave;
	}
	
	public boolean isTieDestination() {
		return tieDestination;
	}
	
	public void setTieDestination(boolean tieDestination) {
		this.tieDestination = tieDestination;
	}

	public boolean isMutedEnabled() {
		return mutedEnabled;
	}

	public void setMutedEnabled(boolean mutedEnabled) {
		this.mutedEnabled = mutedEnabled;
	}

	public boolean isPalmMutedEnabled() {
		return palmMutedEnabled;
	}

	public void setPalmMutedEnabled(boolean palmMutedEnabled) {
		this.palmMutedEnabled = palmMutedEnabled;
	}

	public boolean isSlide() {
		return slide;
	}

	public void setSlide(boolean slide) {
		this.slide = slide;
	}

	public int getSlideFlags() {
		return SlideFlags;
	}

	public void setSlideFlags(int SlideFlags) {
		this.SlideFlags = SlideFlags;
	}

	public boolean isVibrato() {
		return vibrato;
	}

	public void setVibrato(boolean vibrato) {
		this.vibrato = vibrato;
	}

	public boolean isTapped() {
		return Tapped;
	}

	public void setTapped(boolean Tapped) {
		this.Tapped = Tapped;
	}

	public int getElement() {
		return element;
	}

	public void setElement(int element) {
		this.element = element;
	}

	public int getVariation() {
		return variation;
	}

	public void setVariation(int variation) {
		this.variation = variation;
	}

	public int getMidiNumber() {
		return midiNumber;
	}

	public void setMidiNumber(int midiNumber) {
		this.midiNumber = midiNumber;
	}
	
	public int getBendOriginValue() {
		return BendOriginValue;
	}

	public void setBendOriginValue(int BendOriginValue) {
		this.BendOriginValue = BendOriginValue;
	}

	public int getBendMiddleValue() {
		return BendMiddleValue;
	}

	public void setBendMiddleValue(int BendMiddleValue) {
		this.BendMiddleValue = BendMiddleValue;
	}

	public int getBendDestinationValue() {
		return BendDestinationValue;
	}

	public void setBendDestinationValue(int BendDestinationValue) {
		this.BendDestinationValue = BendDestinationValue;
	}

	public boolean getBendEnabled() {
		return BendEnabled;
	}

	public void setBendEnabled(boolean BendEnabled) {
		this.BendEnabled = BendEnabled;
	}

	public boolean isHarmonic() {
		return this.Harmonic;
	}
	
	public int getHarmonicFret() {
		return HarmonicFret;
	}

	public void setHarmonicFret(int HarmonicFret) {
		this.Harmonic = true;
		this.HarmonicFret = HarmonicFret;
	}

	public String getHarmonicType() {
		return HarmonicType;
	}

	public void setHarmonicType(String HarmonicType) {
		this.Harmonic = true;
		this.HarmonicType = HarmonicType;
	}

	public void setHammer(boolean Hammer) {
		this.hammer = Hammer;
	}

	public boolean isHammer() {
		return this.hammer;
	}
}
