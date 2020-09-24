Take note that all "  id " s are primary keys with indexable option on ! .
and go to the Identity Specification tab in the properties culomn and set it yes , increase by 1 .

First table name "Add_Items" 

Culomn name 	Data Type		Allow nulls
---------------------------	------------------		---------------------
id		int		Unchecked
Date		varchar(50)	Checked
Code		varchar(50)	Checked
Item		varchar(50)	Checked
Unit		varchar(50)	Checked
Balance		int		Checked
Registered_By	varchar(50)	Checked
Comment		varchar(100)	Checked
Critical_number	int		Checked


Second Table "Received_Items"

Culomn name 	Data Type		Allow nulls
---------------------------	------------------		---------------------
id		int		Unchecked
Code		varchar(50)	Checked
Date		varchar(50)	Checked
Item		varchar(50)	Checked
Quantity_Received	int		Checked
Unit		varchar(50)	Checked
Serail_No		varchar(50)	Checked
Received_By	varchar(50)	Checked
Comment		varchar(100)	Checked



Third table "Released_Items"

Culomn name 	Data Type		Allow nulls
---------------------------	------------------		---------------------
id		int		Unchecked
Date		varchar(50)	Checked
Code		varchar(50)	Checked
Item		varchar(50)	Checked
Quantity_Released	int		Checked
Unit		varchar(50)	Checked
serial_no		varchar(50)	Checked
Released_By	varchar(50)	Checked
Comment		varchar(100)	Checked
			
Last Table" stock1"


Culomn name 	Data Type		Allow nulls
---------------------------	------------------		---------------------
id		int		Unchecked
Code		varchar(50)	Checked
Item		varchar(50)	Checked
Quantity		int		Checked
Critical_Nomber	int		Checked