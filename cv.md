###### Resume
# Tatyana Pogudo
**+375293277543**
**+375177572467**
## My thoughts
JavaScript or JS is the language of the Internet. Almost all of the most popular pages on the global network use JavaScript. JS is the most popular browsers in the world, such as Google Chrome, Firefox and Internet Explorer. This language can provide stable work and lead to success.
## Skills: 
* basic knowledge of JS;
*CSS;
*Java;
*C++;
* HTML5;
## A piece of my code
```
Data_base::Data_base()
{
	ifstream input("Data_Base.txt");
	string str;
	int i(0);
	while (!input.eof())
	{
		getline(input, str);
		mas[i].num = str;
		getline(input, str);
		mas[i].name = str;
		getline(input, str);
		mas[i].type = str;
		getline(input, str);
		mas[i].bank = str;
		getline(input, str);
		mas[i].cash = str;
		getline(input, str);
		mas[i].pin = str;
		i++;
	}
	count_num = i;
	input.close();
}

void Data_base::updDataBase()
{
	ofstream output("Data_Base.txt");
	int i(0);
	for (int i = 0; i < count_num; i++)
	{
		output << mas[i].num << endl;
		output << mas[i].name << endl;
		output << mas[i].type << endl;
		output << mas[i].bank << endl;
		output << mas[i].cash << endl;
		output << mas[i].pin << endl;
	}
	output.close();
}

```
## Experience
### Higher education  
At the moment I get experience at the university. All labs were written in programming languages, that were written before that.
I am study at BSUIR
.I have a basic knowledge of English. 
The practice of English was at school and university, also online courses and video tutorials on the Internet.
## Languages  
English — A2 — Elementary.  
