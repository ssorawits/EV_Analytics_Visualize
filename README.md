# Mini-Project : ส่อง Mega trend “EV Car”
สำหรับ Mini-project นี้จะประกอบไปด้วยการนำเสนอ 4 ส่วนได้กัน ได้แก่

Part 1: จะเป็นพาไปทำความรู้จักเกี่ยวกับสถานการณ์ EV Car นับตั้งแต่ปี 2010 จนถึงปี 2021 ว่ามีอัตราการเติบโตเป็นอย่างไร ยอดการซื้อรถ EV และสัดส่วนการซื้อรถ EV เมื่อเทียบกับรถประเภทอื่นในแต่ละประเทศเป็นอย่างไร เป็นต้น

Part 2: จะเป็นข้อมูลเกี่ยวกับการคาดการณ์ยอดขาย EV Car ในปี 2025 และปี 2030 ที่ทาง IEA ได้ทำการสำรวจและเก็บข้อมูลโดยอ้างอิงจากนโยบายของประเทศต่างๆ ที่เกี่ยวข้องกับรถ EV และสิ่งแวดล้อม

Part 3: จะเป็นการเปรียบเทียบค่ายรถยนต์ EV ยักษ์ใหญ่ ซึ่งได้แก่ Tesla และ BYD ว่าแต่ละบริษัทมี Fundamental อย่างไร และบริษัทไหนที่น่าจะให้ผลตอบแทนที่ดีกว่าและมี Valuation ที่ถูกกว่าในอนาคต (ข้อมูลคาดการณ์ปี 2022 - 2024)

Part 4: จะเป็นการทดลองหา Portfolio Optimization โดยใช้ Modern Portfolio theory method โดยสินทรัพย์ที่จะทำการลงทุนจะเป็น ETF จำนวน 4 ตัวเพื่อกระจายความเสี่ยง และลงทุนร่วมกับหุ้นบริษัท EV Car หรืออยู่ใน Auto Truck Manufacturers Industries อีก 5 บริษัท

## Part 1: สถานการณ์ EV Car ในอดีตและปัจจุบัน
จากการ Research Data ที่ IEA หรือ International Energy Agency ได้เก็บรวบรวมไว้ พบว่า ยอดขายรถ EV การเติบโตที่เร่งตัวถึง 75.31% CAGR จากจำนวนเพียงไม่กี่พันคันในปี 2010 มาอยู่ที่ 6.53 ล้านคันในปี 2021 ทำให้สัดส่วนยอดขายรถ EV เพิ่มขึ้นมาอยู่ที่ 8.64% ของยอดขายรถยนต์ทั้งหมดในปี 2021

ซึ่งจากข้อมูลดังกล่าวจะเห็นได้ว่า ถึงแม้ยอดขายรถ EV Car จะมีการเติบโตอย่างก้าวกระโดด แต่ก็ยังเป็นเพียงแค่จุดเริ่มต้นเท่านั้น ตลาด EV Car ยังมี Upside หรือศักยภาพในการเติบโตได้อีกมากในอนาคต เห็นได้จากสัดส่วนยอดขายรถ EV ซึ่งคิดเป็นแค่ 8.64% ของยอดขายรถยนต์ทั้งหมดเท่านั้น

![evsale](https://user-images.githubusercontent.com/99993025/196057870-22db94c8-db75-4d86-b9e2-979cf875cc07.png)
![image](https://user-images.githubusercontent.com/99993025/195964427-e585bbfe-8487-484b-9eb5-9e842c0a63d3.png)
![image](https://user-images.githubusercontent.com/99993025/195964473-b9e40506-20fe-4e59-94c5-22d8ce6f8e37.png)


เมื่อพิจารณายอดขายรถ EV รายทวีปพบว่ายอดขายรถ EV กว่า 54% มาจากทวีปเอเชีย รองลงมาคือทวีปยุโรป และ Nort America ที่ 34 และ 11% ตามลำดับ

![image](https://user-images.githubusercontent.com/99993025/195964478-1ebae578-a240-4c2b-a2eb-3b76dd74942f.png)


เมื่อทำการ Breakdown ไปยังรายประเทศพบว่า ประเทศที่มีการซื้อรถ EV Average 5 ปีย้อนหลังมากที่สุดในโลกนั้นก็คือประเทศจีนที่มียอดขายรถ EV อยู่ที่ 1.44 ล้านคันต่อปี มากกว่าอันดับ 2 อย่างสหรัฐอเมริกาถึง 4 เท่า

![image](https://user-images.githubusercontent.com/99993025/195964509-790e30be-a6ca-49c7-b4ac-642f65d064a0.png)


และเมื่อพิจารณาในแง่ของอัตราการเติบโตของยอดขายรถ EV 5 ปีย้อนหลังจะพบว่ามีอัตราการเติบโตของยอดขายเฉลี่ย 58.6% และประเทศส่วนใหญ่มีอัตราการเติบโตของยอดขายรถ EV มากกว่าค่าเฉลี่ย

![image](https://user-images.githubusercontent.com/99993025/195964734-f9bf45c1-a91c-4bac-b2c1-bc8f5b3640ee.png)


ในขณะที่หากพิจารณาสัดส่วนยอดขายรถ EV หรือ Market Share ในปี 2021 นั้นจะพบว่า 
* ถึงแม้ประเทศจีนจะมียอดซื้อรถยนต์มากที่สุดในโลก แต่ประเทศที่มีสัดส่วนการซื้อรถ EV มากเป็นอันดับต้นๆ คือ กลุ่มประเทศในแถบสแกนดิเนเวีย โดนเฉพาะนอร์เวย์ที่มียอดขายรถ EV คิดเป็น 86% เมื่อเทียบกับยอดซื้อรถยนต์ทั้งหมด
* และในส่วนของประเทศจีน พบว่ามีสัดส่วนยอดขายรถ EV คิดเป็นเพียง 16% ของยอดขายรถยนต์ทั้งหมดเท่านั้น
* ขณะที่ประเทศสหรัฐอเมริกากลับมีสัดส่วนการซื้อรถ EV เพียงแค่ 4.56% ซึ่งต่ำกว่าค่าเฉลี่ยอยู่เกือบ 1 เท่าตัว

![image](https://user-images.githubusercontent.com/99993025/195964930-3f4c8db2-a2bb-4ffe-b2a9-23f03e223f33.png)


ทั้งนี้หากเราทำการพลอตกราฟระหว่างค่าเฉลี่ยของยอดขาย และการเติบโตของยอดขายจะพบว่า มีเพียง 3 ประเทศเท่านั้นที่มีทั้งจำนวนยอดขาย และอัตราการเติบโตที่สูงกว่าประเทศอื่นๆ นั้นก็คือ จีน เยอรมัน และฝรั่งเศส

![image](https://user-images.githubusercontent.com/99993025/195964884-f45790f9-5b29-4a1c-8475-c001f28957e4.png)


## Part 2: คาดการณ์สถานการณ์ EV Car ในอนาคต
จากข้อมูลของ IEA ที่ได้มีการคาดการณ์จากโดยอ้างอิงจากนโยบายของประเทศต่างๆ ที่เกี่ยวข้องกับรถ EV และสิ่งแวดล้อม พบว่า ยอดขายรถ EV ทั่วโลกจะเพิ่มขึ้นอย่างก้าวกระโดดในปี 2030 โดยเพิ่มขึ้นจาก 6.57 ล้านคันในปี 2021 มาอยู่ที่ 15.7-19.7 ล้านคันในปี 2025 และ 27.7-43.2 ล้านคันในปี 2030 (ค่าเฉลี่ย:17.7 ล้านคันในปี 2025 และ 35.43 ล้านคันในปี 2030) โดยประเทศจีนจะยังคงครองส่วนแบ่งตลาดมากที่สุด รองลงมาคือประเทศทวีปยุโรป และสหรัฐอเมริกา ขณะที่ประเทศอินเดียเองก็มีแนวโน้มในการเติบโตมากในอนาคต จากการนโยบายสนับสนุนรถ EV และตลาดที่ใหญ่ของประเทศอินเดีย

![image](https://user-images.githubusercontent.com/99993025/195964990-d924f74e-291d-45a4-b855-c7077d1070e1.png)
![ev_fc](https://user-images.githubusercontent.com/99993025/195965060-f07cfaaf-87ce-4272-8a78-9fcfd4c641ae.png)
หมายเหตุ:
* Announced Pledges Scenario (APS): คาดการณ์โดยอิงกับนโยบายหรือมาตรการของประเทศต่างๆ ที่เกี่ยวข้องกับรถ EV และเป้าหมายด้านสิ่งแวดล้อม
* Stated Policies Scenario (STEPS): คาดการณ์โดยอิงกับนโยบายหรือมาตรการของประเทศต่างๆ ที่เกี่ยวข้องกับรถ EV


## Part 3: เปรียบเทียบค่ายรถยนต์ EV ยักษ์ใหญ่ "Tesla vs. BYD"
ในส่วนนี้จะเป็นการเข้าไปทำความเข้าใจถึงโครงสร้างรายได้ของบริษัท รวมถึง Financial Ratio ต่างๆ เพื่อทำการเปรียบเทียบกัน เช่น EPS Ratio, EOA, ROE เป้นต้น

### 1. Revenue
จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี Revenue โดยเฉลี่ยแล้วประมาณ 62,340 Million USD ต่อปี ขณะที่การเติบโตของรายได้นั้นโตเฉลี่ยประมาณ 48% ต่อปี
- BYD มี Revenue โดยเฉลี่ยแล้วประมาณ 39,606 Million USD ต่อปี ขณะที่การเติบโตของรายได้นั้นโตเฉลี่ยประมาณ 27% ต่อปี
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ Revenue Growth นั้นจะพบว่า Tesla ชนะ BYD ไปในยกแรก
![rev tes byd](https://user-images.githubusercontent.com/99993025/195965159-b5641380-4241-4ff8-977c-55ad98856938.png)
Note: BYD Revenue Converted from CNY to USD at 0.139 exchange rate

เมื่อ Breakdown ไปยังรายได้ของธุรกิจของ Tesla จะพบว่าในครึ่งปีแรกของปี 2022 นั้น Tesla มีรายได้จากธุรกิจ 3 ประเภท ซึ่งได้แก่ Automotive คิดเป็นสัดส่วน 88.2%, Services and other 7.69% และ Energy generation and storage 4.15%

![rev_test](https://user-images.githubusercontent.com/99993025/196054328-11b94a2e-8a67-45b8-ab58-f3e1083cf8ac.png)


ขณะที่สัดส่วนรายได้ครึ่งปีแรกของปี 2022 นั้นพบว่า BYD มีรายได้จาก 2 ธุรกิจหลัก ซึ่งส่วนใหญ่นั้นเป็น Automobiles and related product and pther products 73.8% และธุรกิจ Mobile handset components, assembly and related sevice and other products 29.2% ซึ่งจริงๆ แล้ว BYD เป็นหนึ่งในซัพพลายเออร์หลักของสมาร์ทโฟนและพีซี NB ทั่วโลก ส่งผลให้เป็นผู้นำในอุตสาหกรรมอิเล็กทรอนิกส์ด้วยเทคโนโลยีที่ล้ำ มี Intelligent processes และบริการโซลูชั่นครบวงจร

![rev_byd](https://user-images.githubusercontent.com/99993025/196054319-9f0a3c19-9ea2-49a4-9120-8ff38823cecc.png)


### 2. Net Income
จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี Net Income โดยเฉลี่ยแล้วประมาณ 7,135 Million USD ต่อปี ขณะที่การเติบโตของ Net Income นั้นโตเฉลี่ยประมาณ 115% ต่อปี
- BYD มี Net Income โดยเฉลี่ยแล้วประมาณ 1,168 Million USD ต่อปี ขณะที่การเติบโตของ Net Income นั้นโตเฉลี่ยประมาณ 48% ต่อปี
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ Net Income Growth นั้นจะพบว่า Tesla ชนะ BYD ไปได้อีกเช่นกัน

![net_income](https://user-images.githubusercontent.com/99993025/196056304-3d586338-6860-4d58-bd31-f306dd6833d6.png)


### 3. Earnings per Share (EPS)
“EPS” (Earnings per Share) หรือกำไรต่อหุ้น เป็นอัตราส่วนทางการเงินที่เปรียบเทียบระหว่าง “กำไรสุทธิ (Net Profit)” และ “จำนวนหุ้นบริษัทที่ชำระแล้ว (Outstanding Shares)”
โดยทั่วไปแล้ว “EPS” ยิ่งสูงยิ่งดี เพราะแสดงให้เห็นว่าบริษัทนั้นมี “กำไรสุทธิ” ที่สูง ในทางกลับกันถ้า EPS มีค่าต่ำก็จะแสดงให้เห็นว่าบริษัทนั้นมีความสามารถในการทำกำไรที่ต่ำ

จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี EPS โดยเฉลี่ยแล้วประมาณ 1.87 USD/Shares ขณะที่การเติบโตของ EPS นั้นโตเฉลี่ยประมาณ 115% ต่อปี
- BYD มี EPS โดยเฉลี่ยแล้วประมาณ 0.37 USD/Shares ขณะที่การเติบโตของ EPS นั้นโตเฉลี่ยประมาณ 47% ต่อปี
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ EPS Growth นั้นจะพบว่า Tesla ชนะ BYD ไปได้อีกเช่นกัน

![eps](https://user-images.githubusercontent.com/99993025/196199614-7d7127e7-81fe-4bdc-8f46-ab3aff182b18.png)


### 4. EBITDA
“EBITDA หรือ Earnings Before Interest, Tax, Depreciation, and Amortization คือ ตัววัดความสามารถในการทำกำไรจากการดำเนินงานของบริษัท ซึ่งเป็นกำไรก่อนหักดอกเบี้ย, ภาษี, ค่าเสื่อมราคา และค่าตัดจำหน่าย หรือพูดง่าย ๆ ว่า คือ “กำไรจากการดำเนินงานในส่วนที่เป็นเงินสด” จริง ๆ นั่นเอง เพราะเป็นกำไรหลังหักค่าใช้จ่ายที่เกี่ยวกับการดำเนินงาน และบวกค่าเสื่อมต่าง ๆ ที่หักทางบัญชี 

EBITDA margin คือการนำ EBITDA ไปหาเป็น%ของรายได้ทั้งหมด ทำให้เราสามารถทราบได้ว่า ต่อรายได้หนึ่งบาท บริษัทสามารถทำกำไรที่แท้จริงได้เท่าไหร่ ซึ่งตัวเลขตรงนี้ สามารถนำมาเปรียบเทียบทั้งกับผลการดำนานงานย้อนหลัง (time-series) และสามารถเปรียบเทียบกับบริษัทอื่นๆ (cross-sectional) ได้อย่างมีประสิทธิภาพโดยที่ไม่มีผลกระทบจากความแตกต่างทางนโยบายการเงินบัญชีของต่างบริษัท ซึ่งโดยทั่วไปแล้ว EBITDA margin ยิ่งมีค่าสูงก็ยิ่งดี เพราะนั่นแปลว่าธุรกิจสามารถสร้างกำไรหรือผลตอบแทนได้มาก โดย
- EBITDA margin > 0 หรือ เป็นบวก หมายความว่าบริษัทยังมีกำไรจากการดำเนินงาน
- EBITDA margin < 0 หรือ เป็นลบ หมายความว่าบริษัทขาดทุน

จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี EBITDA โดยเฉลี่ยแล้วประมาณ 13,223 Million USD ต่อปี มี EBITDA Margin เฉลี่ยแล้ว 24% ขณะที่การเติบโตของ EBITDA นั้นโตเฉลี่ยประมาณ 456% ต่อปี
- BYD มี EBITDA โดยเฉลี่ยแล้วประมาณ 3,451 Million USD ต่อปี มี EBITDA Margin เฉลี่ยแล้ว 10% ขณะที่การเติบโตของ EBITDA นั้นโตเฉลี่ยประมาณ 27% ต่อปี
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ EBITDA Growth และ EBITDA Margin นั้นจะพบว่า Tesla ชนะ BYD ไปได้อีกเช่นกัน

![ebitda](https://user-images.githubusercontent.com/99993025/196056331-4a757ccf-9080-46a9-896a-9b710722be4b.png)


### 5. ROA Ratio
Return on asset (ROA) คือ อัตราผลตอบแทนจากสินทรัพย์ เป็นสัดส่วนระหว่างกำไรสุทธิ (Net Profit) และสินทรัพย์รวม (Asset) ซึ่งวัดผลออกมาเป็นเปอร์เซ็นต์ บ่งบอกว่าบริษัททำกำไรได้มากน้อยเท่าไรเมื่อเทียบกับสินทรัพย์รวมของบริษัทนั้น ยิ่ง ROA สูงบ่งบอกว่าบริษัทสามารถนำสินทรัพย์ไปสร้างกำไรสุทธิได้มากซึ่งแสดงให้เห็นถึงความมีประสิทธิภาพของบริษัท โดย
- ROA > 0 หมายถึง บริษัทสามารถสร้างกำไรสุทธิจากสินทรัพย์ได้
- ROA < 0 หมายถึง บริษัทไม่สามารถสร้างกำไรสุทธิจากสินทรัพย์ได้

จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี ROA โดยเฉลี่ยแล้วประมาณ 8% 
- BYD มี ROA โดยเฉลี่ยแล้วประมาณ 2% 
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ ROA นั้นจะพบว่า Tesla ชนะ BYD ไปได้อีกเช่นกัน

![roa](https://user-images.githubusercontent.com/99993025/196202211-0dc1bb8b-a0f7-4b05-8543-dbc106429ad6.png)


### 6. ROE Ratio
ROE (Return on Equity) คือ อัตราส่วนที่ช่วยวัดประสิทธิภาพของบริษัทว่าสามารถสร้างผลตอบแทนจากส่วนของเจ้าของหรือส่วนของผู้ถือหุ้นได้มากน้อยเพียงใด ยิ่ง ROE มีค่าสูงก็ยิ่งดี เพราะนั่นแปลว่าธุรกิจสามารถสร้างกำไรหรือผลตอบแทนให้กับผู้ถือหุ้นได้มาก โดย
- ถ้า ROE > 0 หรือเป็นบวก หมายความว่าทางบริษัทสามารถสร้างผลตอบแทนให้ผู้ถือหุ้นได้
- ถ้า ROE < 0 หรือติดลบ หมายความว่าทางบริษัทขาดทุน และไม่สามารถสร้างผลตอบแทนได้ให้ผู้ถือหุ้นได้

จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี ROE โดยเฉลี่ยแล้วประมาณ 11%
- BYD มี ROE โดยเฉลี่ยแล้วประมาณ 8%
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ ROA นั้นจะพบว่า Tesla ชนะ BYD ไปได้อีกเช่นกัน

![roe](https://user-images.githubusercontent.com/99993025/196202196-d6ef697e-13df-45e6-bff9-04c899679ecd.png)


### 7. P/S Ratio
P/S Ratio หรือ Price to Sales Ratio คือ อัตราส่วนที่ใช้ประเมินมูลค่าหุ้นหรือมูลค่าการลงทุน เพื่อทำให้รู้ว่าราคาที่จ่ายไปนั้นถูกหรือแพงกว่าราคาหุ้นในปัจจุบัน โดยการเปรียบเทียบมูลค่าบริษัทตามราคาตลาดกับยอดขาย โดย
- P/S Ratio ต่ำ หมายถึง ได้รับหุ้นในราคาที่ถูก หรือหุ้นนั้นถูกประเมินมูลค่าในราคาต่ำกว่าที่ควรจะเป็น
- P/S Ratio สูง หมายถึง ได้รับหุ้นในราคาที่แพง หรือหุ้นนั้นมีราคาสูงเกินกว่าที่ควรจะเป็น

จากข้อมูลย้อนหลังไปตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 นั้นพบว่า
- Tesla มี P/S Ratio โดยเฉลี่ยแล้วประมาณ 13 เท่า
- BYD มี P/S Ratio โดยเฉลี่ยแล้วประมาณ 2 เท่า
- ฉะนั้นหากเปรียบเทียบกันในส่วนของ P/S Ratio นั้นจะพบว่า BYD กลับมาพลิกชนะ Tesla ได้เนื่องจากมี P/S ที่ถูกกว่า

![ps](https://user-images.githubusercontent.com/99993025/196056429-fb9e1bfc-90e7-48a8-9854-fc677ec80167.png)

### สรุป
หากพิจารณาข้อมูลย้อนหลังตั้งแต่ปี 2017 จนถึงข้อมูลคาดการณ์ปี 2024 ทั้งหมด 7 ด้าน จะสามารถสรุปได้ดังนี้
1. Revenue Growth : Tesla Win!
2. Net Income Growth : Tesla Win!
3. EPS Growth : Tesla Win!
4. EBITDA Growth : Tesla Win!
5. ROA Ratio : Tesla Win!
6. ROE Ratio : Tesla Win!
7. P/S Ratio : BYD Win!
จะเห็นได้ว่า Tesla สามารถเอาชนะ BYD ได้อย่างขาดลอย ยกเว้น P/S Ratio ซึ่งเป็นหนึ่งในตัวชี้วัดความถูกหรือแพงของหุ้น (โดยเฉพาะหุ้น Growth) โดยเบื้องต้นที่ BYD สามารถเอาชนะไปได้เท่านั้น

### แล้วถ้าเราพิจารณาโดยใช้แค่ข้อมูล Forecasts ผลลัพธ์จะออกมาเป็นอย่างไร?
จะเห็นได้ว่าหากเราใช้ข้อมูลในอดีตร่วมกับข้อมูลการคาดการณ์ Tesla จะสามารถเอาชนะ BYD ได้อย่างขาดลอย ส่วนหนึ่งน่าจะมาจากการที่ Tesla มีฐานที่สูงมากในอดีต จึงทำให้ค่าเฉลี่ยออกมาสูงกว่า เพราะฉะนั้นในส่วนนี้จะลองใช้แค่ข้อมูลการคาดการณ์ในการเปรียบเทียบเท่านั้น เพื่อต้องการดูว่าหากใช้เฉพาะข้อมูลคาดการณ์ Tesla หรือ BYD ใครจะชนะ!
โดยในส่วนนี้จะขอนนำเสนอมุมมองการเปรียบเทียบที่สำคัญๆ แค่ 3 มุมมองเท่านั้น ดังนี้

### 1. Foeward EPS Growth & PS Ration Compare
เปรียบเทียบระหว่าง Financial ratio 2 ตัว นั้นคือ
*	Forward EPS Growth ซึ่งจะเป็นหนึ่งใน Guidance ที่จะบอกถึงการเติบโตของกำไรต่อหุ้นของกิจการ
*	Price to sale ratio ซึ่งจะบอกถึงความถูกแพงของกิจการเบื้องต้น และเหมาะสมกับหุ้น Growth มากกว่าการใช้ PE Ratio 
*	พบว่า ไม่ว่าจะเป็นข้อมูลคาดการ์ณของปีนี้, ปีหน้า, และปีถัดไป นั้น BYD ก็ยังคงเหนือกว่า Tesla อย่างชัดเจน ทั้งในแง่ของ Forward EPS Growth ที่สูงกว่า และ Price to sale ที่ต่ำกว่า ดังรูป

![eps_ps](https://user-images.githubusercontent.com/99993025/196056470-d0ac1ed7-0652-45f0-a819-75cf0b51183a.png)


### 2. Foeward EPS Growth & PE Ration Compare
จากการเปรียบเทียบกันโดยใช้ 2022-2024 Forward EPS Growth และ PE Ratio พบว่า"BYD เป็นหุ้นที่มีคุณภาพดีกว่า Tesla" เนื่องจาก Forward EPS Growth สูงกว่า อีกทั้งยังมี Forward PE Ratio ที่ต่ำกว่า

![rps_pe](https://user-images.githubusercontent.com/99993025/196056483-99534654-130b-4de8-bb52-cbb1257c7a63.png)


### 3. Upside 
เปรียบเทียบ Upside ของ Tesla และ BYD โดยพิจารณาจาก Target Price ที่นักวิเคราะห์ได้ให้ Guidance ไว้
ก่อนอื่นเราต้องมาพิจารณา Target Price ก่อนว่ามีลักษณะข้อมูลแบบใด เพื่อที่จะได้นำมาใช้ได้อย่างเหมาะสม ซึ่งจากการ Visualisation เราจะพบว่า Target Price Distibution ของ BYD จะมีลักษณะใกล้เคียงกับ Normal Distribution แต่เมื่อพิจารณา Target Price Distibution ของ Tesla พบว่าไม่เป็น Normal Distribution ฉะนั้นจึงจะใช้ Median Target Price มาเพื่อคำนวณ Upside

![tp-t](https://user-images.githubusercontent.com/99993025/195966415-37009815-70ec-49a9-b434-1db8435dc622.png)
![tp-b](https://user-images.githubusercontent.com/99993025/195966417-5224f1bf-7462-4bd2-86b5-1befa65c00e9.png)

หากพิจารณาค่า Median Target Price ที่นักวิเคราะห์ส่วนใหญ่ให้มุมมองไว้ จะพบว่า BYD มี Upside มากกว่า Tesla โดย
* BYD มี Target Price เท่ากับ 389 CNY หรือคิดเป็น Upside 54.86% จากราคาปัจจุบัน
* Teslaมี Target Price เท่ากับ 325 USD คิดเป็น Upside 45.77% จากราคาปัจจุบัน

![upside](https://user-images.githubusercontent.com/99993025/196056491-031742d3-ad00-430b-890a-df2bc3431905.png)


สรุปหากใช้เฉพาะข้อมูลการคาดการณ์ปี 2022 - 2024 นั้นจะพบว่า BYD มีความน่าลงทุนมากกว่า Tesla ในระยะ 2-3 ปีต่อจากนี้ เนื่องจากมี EPS Growth ที่สูงกว่า, Upside มากกว่า ขณะที่มุมมองเชิง Valuation ไม่ว่าจะใช้ P/S Ration ที่เหมาะสำหรับหุ้น Growth มากกว่า หรือ P/E Ration ก็ตาม BYD ก็ยังมีมูลค่าที่ถูกกว่า Tesla

ทั้งนี้โดยส่วนตัวแล้วทั้ง Tesla และ BYD ก็ยังเป็นบริษัทยักษ์ใหญ่และเป็นผู้นำด้าน EV Car และในส่วนตัวแล้วนั้น หากต้องการที่จะลงทุนในบริษัท EV Car กระผมเองก็คงจะลงทุนทั้ง 2 บริษัท แต่คำถามคือหากเราต้องการจัดพอร์ตการลงทุนเพื่อในระยะยาว โดยเน้นลงทุนโดยตรงในหุ้น EV Car และผสมสินทรัพย์อื่นๆ เช่น ETF ที่ลงทุนในหุ้นทั่วโลก บริษัทด้าน Healthcare หรืออสังหาริมทรัพย์ เป็นต้นนั้น ควรจะลงทุนในแต่ละสินทรัพย์หรือแต่ละบริษัทในสัดส่วนเท่าใดจึงจะเหมาะสม
ซึ่งประเด็นคำถามนี้ จึงนำมาสู่หัวข้อในส่วนถัดไปที่จะนำเสนอ


## Part 4: Portfolio Optimization
ก่อนที่จะไปทำ Portfolio Optimization เพื่อหาสัดส่วนการลงทุนในสินทรัพย์ต่างๆ ที่เหมาะสม เรามาเริ่มจากการหาหุ้น EV Car หรือหุ้นใน Auto Truck Manufacturers Industries กันอีก 3 ตัวก่อนดีกว่า โดย Dataset ที่จะนำมาพิจารณานั้นมาจาก Refinitiv Eikon ซึ่งประกอบไปด้วยบริษัททั่วโลกที่ทำธุรกิจเกี่ยวกับ Auto Truck Manufacturers จำนวน 219 บริษัท

เกณฑ์ในการคัดเลือกหลักทรัพย์
1. เลือกบริษัทที่มี Market Cap สูงสุด 100 ลำดับ
2. ตัดบริษัทที่มีข้อมูลไม่สมบูรณ์
3. คำนวณ Upside จากราคาในปัจจุบัน - Target Price
4. เลือกบริษัทโดยใช้เกณฑ์
- มี Upside >= Median Upside
- มี Forward EPS Growth >= Median Forward EPS Growth
- มี Forward P/S Ratio <= Median P/S Ratio
5. จากนั้นเรียงลำดับตาม Upside
6. เลือกมา 3 บริษัทที่คาดว่าจะมี Upside สูงสุด เพื่อจะไปลงทุนกับ Tesla BYD และสินทรัพย์อื่นๆ
7. จำลองสัดส่วนการลงทุนที่เหมาะสม โดยใช้ Modern Portfolio theory method

จาก Condition ที่กำหนด สามารถคัดเลือกบริษัทจาก 219 บริษัท เหลือเพียง 10 บริษัท ดังนี้

![image](https://user-images.githubusercontent.com/99993025/195966866-fa194611-478c-4a6f-b48c-8619ece100f1.png)

* Upside สูงสุด 3 ลำดับได้แก่
- Xpeng Inc	
- K Car Co Ltd	
- Geely Automobile Holdings Ltd	
แต่จะทำการตัด K Car ซึ่งเทรดอยู่ในตลาดหุ้นเกาหลีออก เนื่องจากความไม่สะดวกในการลงทุนโดยตรง และทำการเลือกบริษัทถัดไปแทน นั่นก็คือ Aston Martin แต่เเนื่องจากความไม่สะดวกในการลงทุนโดยตรงเช่นกัน จึงได้ทำการเลือกบริษัท Yadea Group Holdings Ltd	ซึ่งอยู่ในลำดับที่ 5 และเทรดอยู่ในตลาดฮ่องกงซึ่งมีความสะดวกกว่าในการลงทุนโดยตรงแทน

## Portfolio Optimization

การทำ Portfolio Optimization ณ ที่นี้จะใช้ Modern Portfolio theory method โดยดึงข้อมูลราคาหุ้นย้อนหลัง 5 ปี (2017-09-30 ถึง 2022-09-30) ของบริษัทที่ทำธุรกิจเกี่ยวกับ EV Car / Auto Truck Manufacturers Industry 5 บริษัท ซึ่งได้แก่ Tesla, BYD, Xpeng In, Geely Automobile Holdings Ltd และ Yadea Group อีกทั้งยังมีการผสมสินทรัพย์อื่นๆ เพิ่มเติมเพื่อกระจายความเสี่ยง ซึ่งได้แก่
- Vanguard Total World Stock Index Fund (VT)
- iShares Global Healthcare ETF (IXJ)
- iShares Global Infrastructure ETF (IGF)
- iShares Global REIT ETF (REET)

โดยสินทรัพย์ในพอร์ตทั้งหมด 9 ตัวมีอัตราผลตอบแทนสะสม (Cumulative Returns) 5 ปีย้อนหลัง ดังรูป
![cumulative_rerturn](https://user-images.githubusercontent.com/99993025/196059274-40d56362-da92-4486-b6fb-f4585327fe44.png)

และมี Correlation ดังนี้
![corr](https://user-images.githubusercontent.com/99993025/196059302-bc8ce695-03fb-4707-81d6-ea8411e32481.png)
จะเห็นได้ว่าส่วนใหญ่แล้วหุ้นแต่ละตัวมีความสัมพันธ์กันในระดับกลางถึงต่ำ ยกเว้น ETF ที่เพิ่มเข้ามาทั้ง 4 ตัว ซึ่งส่วนใหญ่แล้วจะลงทุนอยู่ในตลาดหุ้นอเมริกาเป็นหลัก จะมีความสัมพันธ์กันค่อนข้างสูง


![EF](https://user-images.githubusercontent.com/99993025/196056558-3863a926-f611-4738-ba53-3e53e6e88429.png)

ผลการทำ Portfolio Optimization ได้แนวทางในการลงทุน 3 พอร์ตด้วยกัน ซึ่งได้แก่
1. Minimum Variance Portfolio : เป็นพอร์ตที่เน้นให้ความผันผวนต่ำที่สุด สามารถคาดหวังผลตอบแทนได้ประมาณ 12% ต่อปี
2. Maximun Sharpe Portfolio : เป็นพอร์ตที่เน้น Sharp Ratio หรือเน้นสร้างอัตราผลตอบแทนเมื่อเทียบกับความเสี่ยงสูงที่สุด สามารถคาดหวังผลตอบแทนได้ประมาณ 31% ต่อปี
3. Maximun Return Portfolio : เป็นพอร์ตที่เน้นสร้างผลตอบแทนให้สูงที่สุด สามารถคาดหวังผลตอบแทนได้ประมาณ 42% ต่อปี

![port_re](https://user-images.githubusercontent.com/99993025/196057277-997ca599-6c57-433c-9e11-69341421c6aa.png)


โดยทั้ง 3 พอร์ตมีสัดส่วนการลงทุนในสินทรัพย์ประเภทต่างๆ ดังนี้

![port_w](https://user-images.githubusercontent.com/99993025/196057381-5c1dede1-2326-4f5f-9ac4-8b5bd8327081.png)
![port_w2](https://user-images.githubusercontent.com/99993025/196057383-5f1fc543-6389-4461-854b-31abbf3fdd5d.png)














