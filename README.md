# Food_Preference_Survey
It's a food prefrence survey form that gives the report of food prefrences by people.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foof Preferences Survey Form</title>
    <style>
        body{
            font-family: sans-serif;
        }
        th,
        td {
            padding: 10px;
        }
        label{
            margin: 20px;
        }
        button{
            margin: 2px;
        }
    </style>
</head>
<body>
    <h1>Food Preferences - Survey Form</h1>
    <h5>Please fill out and submit the survey form at the earliest</h5>
    <hr />
    <form action="" method="post">
        <table> 
            <tr>
                <td>1. Name</td>
                <td> <input type="text" name="user" /> </td>
            </tr>
            <tr>
                <td>2. Age</td>
                <td> <input type="number" name="age" min="13" max="100"/></td>
            </tr>
            <tr>
                <td>3. Where do you eat most often?</td>
                <td>
                    <input type="radio" id="home"name="location" value="home" />
                    <label for="home">at home</label>

                    <input type="radio" id="work_or_school"name="location" value="work_or_school" />
                    <label for="work_or_school">at work / school</label>
                
                    <input type="radio" id="restaurant"name="location" value="restaurant" />
                    <label for="restaurant">at restaurant</label>
                </td>
            </tr>
            <tr>
                <td colspan="2">4. Specify, How often</td>
            </tr>
            <tr>
                <td colspan="2"> 
                    <table style="font-size: 0.7em; border: 1px solid">
                        <thead>
                            <tr>
                                <th></th>
                                <th>every day</th>
                                <th>a few times a week</th>
                                <th>once a week</th>
                                <th>several times a month</th>
                                <th>one a month</th>
                                <th>less often than once a month</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>You prepare your own meals</td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="everyday"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="vew times a week"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="once a week"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="several times a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="once a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_prepare" value="less often than once a moonth"/> </td>
                            </tr>
                            <tr>
                                <td>You eat out</td>
                                <td style="text-align: center;"><input type="radio" name="you_eat_out" value="everyday"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_eat_out" value="vew times a week"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_eat_out" value="once a week"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_eat_out" value="several times a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_eat_out" value="once a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_eat_out" value="less often than once a moonth"/> </td>
                            </tr>
                            <tr>
                                <td>You order food for home</td>
                                <td style="text-align: center;"><input type="radio" name="you_order_food" value="everyday"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_order_food" value="vew times a week"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_order_food" value="once a week"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_order_food" value="several times a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_order_food" value="once a month"/> </td>
                                <td style="text-align: center;"><input type="radio" name="you_order_food" value="less often than once a moonth"/> </td>
                            </tr>
                        </tbody>
                    </table>
                </td>
            </tr>
            <tr>
                <td colspan="2">5. The most common places you visit are restaurants serving food of origin:</td>
            </tr>
            <tr>
                <td colspan="2">
                    <table>
                        <tr>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Polish" value="Polish"/>
                            <label for="Polish">Polish</label>
                        </td>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Indian" value="Indian"/>
                            <label for="Indian">Indian</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Italian" value="Italian"/>
                            <label for="Italian">Italian</label>
                        </td>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Spanish" value="Spanish"/>
                            <label for="Spanish">Spanish</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Asian" value="Asian"/>
                            <label for="Asian">Asian</label>
                        </td>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Chinese" value="Chinese"/>
                            <label for="Chinese">Chinese</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="American" value="American"/>
                            <label for="American">American</label>
                        </td>
                        <td>
                            <input type="checkbox"  name="food _origin_prefrence" id="Others" value="Others"/>
                            <label for="Others">Others</label>
                        </td>
                    </tr>
                    <tr>
                        <td>6. Given an optin, would you go Vegan?</td>
                        <td><input type="radio" name="vegan" id="Sure" value="Sure"/> <label for="Sure">Sure</label></td>
                        <td><input type="radio" name="vegan" id="No" value="No"/> <label for="No">No</label></td>
                    </tr>
                    <tr>
                        <td>
                            <button>Submit</button><button type="Reset">Reset</button>
                        </td>
                    </tr>
                    </table>
                </td>
            </tr>
        </table>
    </form>
</body>
</html>
