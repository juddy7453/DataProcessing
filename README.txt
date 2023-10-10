중고차 가격 예측

Brand & Model: Identify the brand or company name along with the specific model of each vehicle.
Model Year: Discover the manufacturing year of the vehicles, crucial for assessing depreciation and technology advancements.
Mileage: Obtain the mileage of each vehicle, a key indicator of wear and tear and potential maintenance requirements.
Fuel Type: Learn about the type of fuel the vehicles run on, whether it's gasoline, diesel, electric, or hybrid.
Engine Type: Understand the engine specifications, shedding light on performance and efficiency.
Transmission: Determine the transmission type, whether automatic, manual, or another variant.
Exterior & Interior Colors: Explore the aesthetic aspects of the vehicles, including exterior and interior color options.
Accident History: Discover whether a vehicle has a prior history of accidents or damage, crucial for informed decision-making.
Clean Title: Evaluate the availability of a clean title, which can impact the vehicle's resale value and legal status.
Price: Access the listed prices for each vehicle, aiding in price comparison and budgeting

fuel_type에 결측치 170개, accident에 결측치 113개, clean_title에 결측치 596개 존재

fuel_type의 결측치 처리
동일한 모델은 동일한 fuel_type을 가질 것이라고 생각함 -> 같은 model 값에 대하여 같은 fuel_type 값을 갖도록 입력하고, 같은 model 값이 없는 경우에는 fuel_type의 최빈값인 Gasoline으로 채웠다.

accident의 결측치 처리 - 제외

clean_title의 결측치 처리
nan값을 'No'로 변경