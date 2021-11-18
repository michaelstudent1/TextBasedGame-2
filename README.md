# TextBasedGame-2
 int main() {
	switch (room) {
	case 1:
		cout << "You are located room 1. You can go west." << endl;
		cin >> input;
		if (input == 'W')
			room == 2;
		else
			cout << "sorry. thats not a option," << endl;
		break;
	case 2:
		cout << "You are located room 2. You can go South." << endl;
		cin >> input;
		if (input == 'S')
			room == 1;
		else
			cout << "sorry. thats not a option," << endl;
		break;
	case 3:
		cout << "You are located room 1. You can go East." << endl;
		cin >> input;
		if (input == 'E')
			room == 1;
		else
			cout << "sorry. thats not a option," << endl;
		break;
	case 4:
		cout << "You are located room 1. You can go North." << endl;
		cin >> input;
		if (input == 'N')
			room == 1;
		else
			cout << "sorry. thats not a option," << endl;
		break;
	case 5:
		cout << "You are located room 1. You are now located in the Main Room." << endl;
		cin >> input;
		if (input == 'M')
			room == 1;
		else
			cout << "sorry. thats not a option," << endl;
		break;

