# METADATA FOR NATURAL GAS COMMERCIALIZATION  
**SUPERINTENDENCY OF INFRASTRUCTURE AND MOVEMENT**  

---

## 1) Sales to Distributors and Free Consumers  

| **VARIABLE NAME**       | **VARIABLE TYPE** | **DESCRIPTION** |
|-------------------------|-------------------|----------------|
| **YEAR**                | Integer           | Year of gas commercialization |
| **MONTH**               | Integer           | Month of gas commercialization |
| **MARKET TYPE**         | Text              | Market type: "Thermoelectric" or "Non-Thermoelectric" |
| **AGGREGATED REGION**   | Text              | Aggregation of Brazilian geographic regions |
| **PRICE (BRL per MMBtu)** | Real Number     | Weighted average price (including taxes) in BRL per million BTUs |
| **VOLUME (Thousand m³/Day)** | Integer   | Daily average volume (1,000 m³/day) |

---
**Thermoelectric:** This market involves devices like thermoelectric generators (TEGs) and thermoelectric coolers (TECs). TEGs convert heat into electricity, while TECs use electricity to create a temperature difference for cooling. Examples include their use in space, automobiles, and various industrial applications. 

**Non-Thermoelectric:** This category encompasses all other market types that do not involve thermoelectric principles. This could include various industries like food processing, electronics, or other sectors that don't utilize the specific heat-to-electricity or electricity-to-cooling conversion of thermoelectric devices. 

---
## 2) Sales Between Producers  

| **VARIABLE NAME**       | **VARIABLE TYPE** | **DESCRIPTION** |
|-------------------------|-------------------|----------------|
| **YEAR**                | Integer           | Year of gas commercialization |
| **MONTH**               | Integer           | Month of gas commercialization |
| **AGGREGATED BASIN**    | Text              | Aggregation of Brazilian sedimentary basins. *Note:* "Other Basins" excludes Santos and Campos. |
| **PRICE (BRL per MMBtu)** | Real Number     | Weighted average price (including taxes) in BRL per million BTUs |
| **VOLUME (Thousand m³/Day)** | Integer   | Daily average volume (1,000 m³/day) |

---

## Additional Information  

| **FIELD**              | **DETAILS** |
|------------------------|------------|
| **DESCRIPTION**        | Dataset includes: <br> • Sales to distributors/free consumers <br> • Sales between producers <br> *Data aggregated to preserve confidentiality* |
| **SOURCE CATALOG**     | [ANP Open Data Portal](https://www.gov.br/am/pt-br/dados-abertos) |
| **RESPONSIBLE AGENCY** | Superintendency of Infrastructure and Movement (SIM/ANP) |
| **FREQUENCY**          | Monthly |
| **CONTACT**            | [faleconosco@anp.gov.br](mailto:faleconosco@anp.gov.br) |
