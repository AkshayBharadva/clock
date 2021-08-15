# Analog Clock
This is the simple "Analog Clock" to get idea og the conversion function of time to degree to rotate Needle and the use of Quote api to get Insipration! Using Html, Css, Js...

const scale = (num, in_min, in_max, out_min, out_max) => {
	return (
		((num - in_min) * (out_max - out_min)) / (in_max - in_min) + out_min
	);
};

Check out : https://akshaybharadva.github.io/clock/
