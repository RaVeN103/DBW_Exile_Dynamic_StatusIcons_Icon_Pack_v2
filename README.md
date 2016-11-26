# DBW_Exile_Dynamic_StatusIcons_Icon_Pack_v2
Replacement for DBW's Exile Dynamic StatusIcons

ToDo

-Replace the folders 'circlebar' and 'icons'

-Replace the 'statusIcons.sqf'

or

-find

  sb_getIcon = {
        _value = _this select 0;
        _icon = "100";

        if (_value >= 100 ) then 							{ _icon ="100";	};
        if (_value >=90 && _value < 100 ) then 	{ _icon ="90";		};
        if (_value >=80 && _value < 90 ) then 		{ _icon ="80";		};
        if (_value >=70 && _value < 80 ) then 		{ _icon ="70";		};
        if (_value >=60 && _value < 70 ) then 		{ _icon ="60";		};
        if (_value >=50 && _value < 60 ) then 		{ _icon ="50";		};
        if (_value >=40 && _value < 50 ) then 		{ _icon ="40";		};
        if (_value >=30 && _value < 40 ) then 		{ _icon ="30";		};
        if (_value >=20 && _value < 30 ) then 		{ _icon ="20";		};
        if (_value >=10 && _value < 20 ) then 		{ _icon ="10";		};
        if (_value >=1 && _value < 10 ) then 		{ _icon ="1";		};
        if (_value < 1 ) then 								{ _icon ="0";		};

        _icon
      };
 
and replace with

  sb_getIcon = {
      _value = _this select 0;
      _icon = "100";

      if (_value >= 100 ) then 					{ _icon ="100";		};
      if (_value >=95 && _value < 100 ) then 		{ _icon ="95";		};
      if (_value >=90 && _value < 95 ) then 		{ _icon ="90";		};
      if (_value >=85 && _value < 90 ) then 		{ _icon ="85";		};
      if (_value >=80 && _value < 85 ) then 		{ _icon ="80";		};
      if (_value >=75 && _value < 80 ) then 		{ _icon ="75";		};
      if (_value >=70 && _value < 75 ) then 		{ _icon ="70";		};
      if (_value >=65 && _value < 70 ) then 		{ _icon ="65";		};
      if (_value >=60 && _value < 65 ) then 		{ _icon ="60";		};
      if (_value >=55 && _value < 60 ) then 		{ _icon ="55";		};
      if (_value >=50 && _value < 55 ) then 		{ _icon ="50";		};
      if (_value >=45 && _value < 50 ) then 		{ _icon ="45";		};
      if (_value >=40 && _value < 45 ) then 		{ _icon ="40";		};
      if (_value >=35 && _value < 40 ) then 		{ _icon ="35";		};
      if (_value >=30 && _value < 35 ) then 		{ _icon ="30";		};
      if (_value >=25 && _value < 30 ) then 		{ _icon ="25";		};
      if (_value >=20 && _value < 25 ) then 		{ _icon ="20";		};
      if (_value >=15 && _value < 20 ) then 		{ _icon ="15";		};		
      if (_value >=10 && _value < 15 ) then 		{ _icon ="10";		};
      if (_value >=5 && _value < 0 ) then 		{ _icon ="5";		};
      if (_value >=1 && _value < 10 ) then 		{ _icon ="1";		};
      if (_value < 1 ) then 						{ _icon ="0";		};

      _icon
    };    
  
  You're Done!!!
