science q02 spec · JSON
{
  "type": "quiz",
  "title": "Forces, Motion and Speed",
  "year": 8,
  "quiz_number": 2,
  "intro": "Learning objective: to understand forces and motion, including speed. You have 20 minutes.",
  "mode": "test",
  "layout": "paged",
  "duration_minutes": 20,
  "calculator": true,
  "questions": [
    {
      "id": "q1",
      "type": "numeric",
      "objective": "8Pf.01",
      "prompt": "A camel walks 120 m in 40 s.\n\nCalculate its speed.",
      "answer": 3,
      "suffix": "m/s",
      "explanation": "speed = distance ÷ time = 120 m ÷ 40 s = 3 m/s."
    },
    {
      "id": "q2",
      "type": "blanks",
      "objective": "8Pf.01",
      "prompt": "A cyclist rides 3000 m in 10 minutes. Calculate her speed in metres per second (m/s).",
      "text": "10 minutes = [[1]] seconds\nspeed = 3000 ÷ [[1]] = [[2]] m/s",
      "blanks": [
        {
          "answer": 600,
          "type": "numeric",
          "width": 5
        },
        {
          "answer": 5,
          "type": "numeric",
          "width": 5
        }
      ],
      "explanation": "Change minutes to seconds first: 10 × 60 = 600 s. Then speed = 3000 m ÷ 600 s = 5 m/s."
    },
    {
      "id": "q3",
      "type": "mcq",
      "objective": "8Pf.01",
      "shuffle": true,
      "prompt": "Three students ran in a race. Their results are in the table.\n\nWhich student had the <b>highest speed</b>?",
      "table": {
        "headers": [
          "Student",
          "Distance (m)",
          "Time (s)"
        ],
        "rows": [
          [
            "A",
            100,
            20
          ],
          [
            "B",
            60,
            10
          ],
          [
            "C",
            90,
            18
          ]
        ]
      },
      "options": [
        "Student A",
        "Student B",
        "Student C",
        "They all had the same speed."
      ],
      "answer": 1,
      "explanation": "A: 100 ÷ 20 = 5 m/s. B: 60 ÷ 10 = 6 m/s. C: 90 ÷ 18 = 5 m/s. Student B ran the shortest distance but was fastest. The longest distance does not mean the highest speed."
    },
    {
      "id": "q4",
      "type": "mcq",
      "objective": "8Pf.01",
      "prompt": "A coach travels 60 km in the first hour. It then travels another 60 km in the next 2 hours.\n\nWhat is its <b>average speed</b> for the whole journey?",
      "options": [
        "30 km/h",
        "40 km/h",
        "45 km/h",
        "60 km/h"
      ],
      "answer": 1,
      "explanation": "Average speed = total distance ÷ total time = 120 km ÷ 3 h = 40 km/h. 45 km/h comes from averaging 60 and 30, which does not work because the times are different."
    },
    {
      "id": "q5",
      "type": "blanks",
      "objective": "8Pf.01",
      "also": [
        "8TWSa.02"
      ],
      "prompt": "Complete the sentences using Ravi's results.",
      "table": {
        "caption": "Ravi rolled a toy car down a ramp 5 times. It travelled 2.0 m each time.",
        "headers": [
          "Trial",
          "Time for 2.0 m (s)"
        ],
        "rows": [
          [
            1,
            2
          ],
          [
            2,
            2.1
          ],
          [
            3,
            1.9
          ],
          [
            4,
            3.4
          ],
          [
            5,
            2
          ]
        ]
      },
      "text": "The anomalous result is [[1]].\nIgnoring the anomalous result, the average speed of the car is [[2]] m/s.",
      "blanks": [
        {
          "options": [
            "1.9 s",
            "2.0 s",
            "2.1 s",
            "3.4 s"
          ],
          "answer": 3
        },
        {
          "answer": 1,
          "type": "numeric",
          "tolerance": 0.05,
          "width": 5
        }
      ],
      "explanation": "3.4 s does not fit the pattern of the other times, so it is anomalous. The other four times have a mean of 8.0 ÷ 4 = 2.0 s. Speed = 2.0 m ÷ 2.0 s = 1.0 m/s."
    },
    {
      "id": "q6",
      "type": "numeric",
      "objective": "8Pf.02",
      "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 480 340\" width=\"480\" height=\"340\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"72.0\" y1=\"16\" x2=\"72.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"72.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"120.5\" y1=\"16\" x2=\"120.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"120.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >1</text><line x1=\"169.0\" y1=\"16\" x2=\"169.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"169.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"217.5\" y1=\"16\" x2=\"217.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"217.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >3</text><line x1=\"266.0\" y1=\"16\" x2=\"266.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"266.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"314.5\" y1=\"16\" x2=\"314.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"314.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >5</text><line x1=\"363.0\" y1=\"16\" x2=\"363.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"363.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><line x1=\"411.5\" y1=\"16\" x2=\"411.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"411.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >7</text><line x1=\"460.0\" y1=\"16\" x2=\"460.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"460.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >8</text><line x1=\"72\" y1=\"282.0\" x2=\"460\" y2=\"282.0\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"287.0\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"72\" y1=\"252.4\" x2=\"460\" y2=\"252.4\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"257.4\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >50</text><line x1=\"72\" y1=\"222.9\" x2=\"460\" y2=\"222.9\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"227.9\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >100</text><line x1=\"72\" y1=\"193.3\" x2=\"460\" y2=\"193.3\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"198.3\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >150</text><line x1=\"72\" y1=\"163.8\" x2=\"460\" y2=\"163.8\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"168.8\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >200</text><line x1=\"72\" y1=\"134.2\" x2=\"460\" y2=\"134.2\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"139.2\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >250</text><line x1=\"72\" y1=\"104.7\" x2=\"460\" y2=\"104.7\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"109.7\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >300</text><line x1=\"72\" y1=\"75.1\" x2=\"460\" y2=\"75.1\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"80.1\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >350</text><line x1=\"72\" y1=\"45.6\" x2=\"460\" y2=\"45.6\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"50.6\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >400</text><line x1=\"72\" y1=\"16.0\" x2=\"460\" y2=\"16.0\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"21.0\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >450</text><line x1=\"72\" y1=\"16\" x2=\"72\" y2=\"282\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"72\" y1=\"282\" x2=\"460\" y2=\"282\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><polyline points=\"72.0,282.0 217.5,104.7 314.5,104.7 460.0,16.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3\"/><circle cx=\"72.0\" cy=\"282.0\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"217.5\" cy=\"104.7\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"314.5\" cy=\"104.7\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"460.0\" cy=\"16.0\" r=\"4.5\" fill=\"#5a45b8\"/><text x=\"266.0\" y=\"330.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (minutes)</text><text x=\"16.0\" y=\"149.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 16 149.0)\">Distance from home (m)</text></svg>",
      "prompt": "The graph shows Amira's walk to school.\n\nHow far had she walked after 3 minutes?",
      "answer": 300,
      "suffix": "m",
      "explanation": "Go up from 3 minutes on the time axis to the line, then across to the distance axis: 300 m."
    },
    {
      "id": "q7",
      "type": "mcq",
      "objective": "8Pf.02",
      "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 480 340\" width=\"480\" height=\"340\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"72.0\" y1=\"16\" x2=\"72.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"72.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"120.5\" y1=\"16\" x2=\"120.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"120.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >1</text><line x1=\"169.0\" y1=\"16\" x2=\"169.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"169.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"217.5\" y1=\"16\" x2=\"217.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"217.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >3</text><line x1=\"266.0\" y1=\"16\" x2=\"266.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"266.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"314.5\" y1=\"16\" x2=\"314.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"314.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >5</text><line x1=\"363.0\" y1=\"16\" x2=\"363.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"363.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><line x1=\"411.5\" y1=\"16\" x2=\"411.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"411.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >7</text><line x1=\"460.0\" y1=\"16\" x2=\"460.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"460.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >8</text><line x1=\"72\" y1=\"282.0\" x2=\"460\" y2=\"282.0\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"287.0\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"72\" y1=\"252.4\" x2=\"460\" y2=\"252.4\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"257.4\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >50</text><line x1=\"72\" y1=\"222.9\" x2=\"460\" y2=\"222.9\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"227.9\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >100</text><line x1=\"72\" y1=\"193.3\" x2=\"460\" y2=\"193.3\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"198.3\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >150</text><line x1=\"72\" y1=\"163.8\" x2=\"460\" y2=\"163.8\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"168.8\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >200</text><line x1=\"72\" y1=\"134.2\" x2=\"460\" y2=\"134.2\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"139.2\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >250</text><line x1=\"72\" y1=\"104.7\" x2=\"460\" y2=\"104.7\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"109.7\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >300</text><line x1=\"72\" y1=\"75.1\" x2=\"460\" y2=\"75.1\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"80.1\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >350</text><line x1=\"72\" y1=\"45.6\" x2=\"460\" y2=\"45.6\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"50.6\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >400</text><line x1=\"72\" y1=\"16.0\" x2=\"460\" y2=\"16.0\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"21.0\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >450</text><line x1=\"72\" y1=\"16\" x2=\"72\" y2=\"282\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"72\" y1=\"282\" x2=\"460\" y2=\"282\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><polyline points=\"72.0,282.0 217.5,104.7 314.5,104.7 460.0,16.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3\"/><circle cx=\"72.0\" cy=\"282.0\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"217.5\" cy=\"104.7\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"314.5\" cy=\"104.7\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"460.0\" cy=\"16.0\" r=\"4.5\" fill=\"#5a45b8\"/><text x=\"266.0\" y=\"330.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (minutes)</text><text x=\"16.0\" y=\"149.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 16 149.0)\">Distance from home (m)</text></svg>",
      "shuffle": true,
      "prompt": "In which part of Amira's walk was she moving <b>fastest</b>?",
      "options": [
        "0 to 3 minutes",
        "3 to 5 minutes",
        "5 to 8 minutes",
        "She moved at the same speed all the time."
      ],
      "answer": 0,
      "explanation": "The steepest part of a distance-time graph shows the fastest movement: she walked 300 m in 3 minutes at the start. The flat part from 3 to 5 minutes means she was not moving."
    },
    {
      "id": "q8",
      "type": "numeric",
      "objective": "8Pf.02",
      "also": [
        "8Pf.01"
      ],
      "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 480 340\" width=\"480\" height=\"340\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"72.0\" y1=\"16\" x2=\"72.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"72.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"120.5\" y1=\"16\" x2=\"120.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"120.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >1</text><line x1=\"169.0\" y1=\"16\" x2=\"169.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"169.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"217.5\" y1=\"16\" x2=\"217.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"217.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >3</text><line x1=\"266.0\" y1=\"16\" x2=\"266.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"266.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"314.5\" y1=\"16\" x2=\"314.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"314.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >5</text><line x1=\"363.0\" y1=\"16\" x2=\"363.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"363.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><line x1=\"411.5\" y1=\"16\" x2=\"411.5\" y2=\"282\" stroke=\"#ddd\"/><text x=\"411.5\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >7</text><line x1=\"460.0\" y1=\"16\" x2=\"460.0\" y2=\"282\" stroke=\"#ddd\"/><text x=\"460.0\" y=\"302.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >8</text><line x1=\"72\" y1=\"282.0\" x2=\"460\" y2=\"282.0\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"287.0\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"72\" y1=\"252.4\" x2=\"460\" y2=\"252.4\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"257.4\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >50</text><line x1=\"72\" y1=\"222.9\" x2=\"460\" y2=\"222.9\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"227.9\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >100</text><line x1=\"72\" y1=\"193.3\" x2=\"460\" y2=\"193.3\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"198.3\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >150</text><line x1=\"72\" y1=\"163.8\" x2=\"460\" y2=\"163.8\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"168.8\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >200</text><line x1=\"72\" y1=\"134.2\" x2=\"460\" y2=\"134.2\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"139.2\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >250</text><line x1=\"72\" y1=\"104.7\" x2=\"460\" y2=\"104.7\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"109.7\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >300</text><line x1=\"72\" y1=\"75.1\" x2=\"460\" y2=\"75.1\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"80.1\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >350</text><line x1=\"72\" y1=\"45.6\" x2=\"460\" y2=\"45.6\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"50.6\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >400</text><line x1=\"72\" y1=\"16.0\" x2=\"460\" y2=\"16.0\" stroke=\"#ddd\"/><text x=\"64.0\" y=\"21.0\" font-size=\"13\" text-anchor=\"end\" font-weight=\"normal\" fill=\"#1d1b2c\" >450</text><line x1=\"72\" y1=\"16\" x2=\"72\" y2=\"282\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"72\" y1=\"282\" x2=\"460\" y2=\"282\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><polyline points=\"72.0,282.0 217.5,104.7 314.5,104.7 460.0,16.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3\"/><circle cx=\"72.0\" cy=\"282.0\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"217.5\" cy=\"104.7\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"314.5\" cy=\"104.7\" r=\"4.5\" fill=\"#5a45b8\"/><circle cx=\"460.0\" cy=\"16.0\" r=\"4.5\" fill=\"#5a45b8\"/><text x=\"266.0\" y=\"330.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (minutes)</text><text x=\"16.0\" y=\"149.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 16 149.0)\">Distance from home (m)</text></svg>",
      "prompt": "Calculate Amira's speed between 5 and 8 minutes. Give your answer in metres per minute.",
      "answer": 50,
      "suffix": "m/min",
      "explanation": "Distance = 450 − 300 = 150 m. Time = 8 − 5 = 3 min. Speed = 150 ÷ 3 = 50 m/min."
    },
    {
      "id": "q9",
      "type": "match",
      "objective": "8Pf.02",
      "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 510 190\" width=\"510\" height=\"190\" role=\"img\" aria-label=\"three distance-time graphs A, B and C\" style=\"font-family:Arial,Helvetica,sans-serif\"><text x=\"95.0\" y=\"18.0\" font-size=\"20\" text-anchor=\"middle\" font-weight=\"bold\" fill=\"#1d1b2c\" >A</text><line x1=\"30\" y1=\"34\" x2=\"30\" y2=\"160\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30\" y1=\"160\" x2=\"157\" y2=\"160\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><polyline points=\"30.0,97.0 157.0,97.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"93.5\" y=\"182.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time</text><text x=\"9.0\" y=\"97.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 9 97.0)\">Distance</text><text x=\"265.0\" y=\"18.0\" font-size=\"20\" text-anchor=\"middle\" font-weight=\"bold\" fill=\"#1d1b2c\" >B</text><line x1=\"200\" y1=\"34\" x2=\"200\" y2=\"160\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"200\" y1=\"160\" x2=\"327\" y2=\"160\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><polyline points=\"200.0,160.0 327.0,55.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"263.5\" y=\"182.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time</text><text x=\"179.0\" y=\"97.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 179 97.0)\">Distance</text><text x=\"435.0\" y=\"18.0\" font-size=\"20\" text-anchor=\"middle\" font-weight=\"bold\" fill=\"#1d1b2c\" >C</text><line x1=\"370\" y1=\"34\" x2=\"370\" y2=\"160\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"370\" y1=\"160\" x2=\"497\" y2=\"160\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><polyline points=\"370.0,55.0 497.0,160.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"433.5\" y=\"182.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time</text><text x=\"349.0\" y=\"97.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 349 97.0)\">Distance</text></svg>",
      "prompt": "Each graph shows the journey of a different object. Match each graph to the correct description.",
      "left": [
        "Graph A",
        "Graph B",
        "Graph C"
      ],
      "right": [
        "not moving",
        "moving away at a steady speed",
        "moving back towards the start at a steady speed",
        "moving faster and faster"
      ],
      "answer": [
        0,
        1,
        2
      ],
      "explanation": "A flat line means the distance is not changing, so the object is stopped. A straight sloping line up is a steady speed away. A line sloping down means the distance from the start is getting smaller."
    },
    {
      "id": "q10",
      "type": "mcq",
      "objective": "8Pf.02",
      "columns": 2,
      "prompt": "Omar cycles at a steady speed for 2 minutes, stops for 2 minutes, then cycles on at the <b>same</b> steady speed for 2 minutes.\n\nWhich graph shows his journey?",
      "options": [
        {
          "text": "",
          "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 260 210\" width=\"260\" height=\"210\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"30\" y1=\"8\" x2=\"30\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30\" y1=\"166\" x2=\"252\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30.0\" y1=\"166\" x2=\"30.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"30.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"104.0\" y1=\"166\" x2=\"104.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"104.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"178.0\" y1=\"166\" x2=\"178.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"178.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"252.0\" y1=\"166\" x2=\"252.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"252.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><polyline points=\"30.0,166.0 104.0,113.3 178.0,113.3 252.0,8.0\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"141.0\" y=\"206.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (min)</text><text x=\"9.0\" y=\"87.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 9 87.0)\">Distance</text></svg>"
        },
        {
          "text": "",
          "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 260 210\" width=\"260\" height=\"210\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"30\" y1=\"8\" x2=\"30\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30\" y1=\"166\" x2=\"252\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30.0\" y1=\"166\" x2=\"30.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"30.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"104.0\" y1=\"166\" x2=\"104.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"104.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"178.0\" y1=\"166\" x2=\"178.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"178.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"252.0\" y1=\"166\" x2=\"252.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"252.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><polyline points=\"30.0,166.0 104.0,113.3 178.0,166.0 252.0,113.3\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"141.0\" y=\"206.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (min)</text><text x=\"9.0\" y=\"87.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 9 87.0)\">Distance</text></svg>"
        },
        {
          "text": "",
          "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 260 210\" width=\"260\" height=\"210\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"30\" y1=\"8\" x2=\"30\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30\" y1=\"166\" x2=\"252\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30.0\" y1=\"166\" x2=\"30.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"30.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"104.0\" y1=\"166\" x2=\"104.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"104.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"178.0\" y1=\"166\" x2=\"178.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"178.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"252.0\" y1=\"166\" x2=\"252.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"252.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><polyline points=\"30.0,166.0 104.0,113.3 178.0,113.3 252.0,60.7\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"141.0\" y=\"206.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (min)</text><text x=\"9.0\" y=\"87.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 9 87.0)\">Distance</text></svg>"
        },
        {
          "text": "",
          "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 260 210\" width=\"260\" height=\"210\" role=\"img\" aria-label=\"distance-time graph\" style=\"font-family:Arial,Helvetica,sans-serif\"><line x1=\"30\" y1=\"8\" x2=\"30\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30\" y1=\"166\" x2=\"252\" y2=\"166\" stroke=\"#1d1b2c\" stroke-width=\"2\"/><line x1=\"30.0\" y1=\"166\" x2=\"30.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"30.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >0</text><line x1=\"104.0\" y1=\"166\" x2=\"104.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"104.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >2</text><line x1=\"178.0\" y1=\"166\" x2=\"178.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"178.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >4</text><line x1=\"252.0\" y1=\"166\" x2=\"252.0\" y2=\"8\" stroke=\"#e3e3e3\"/><text x=\"252.0\" y=\"183.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >6</text><polyline points=\"30.0,166.0 104.0,113.3 178.0,60.7 252.0,60.7\" fill=\"none\" stroke=\"#5a45b8\" stroke-width=\"3.5\"/><text x=\"141.0\" y=\"206.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" >Time (min)</text><text x=\"9.0\" y=\"87.0\" font-size=\"13\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" transform=\"rotate(-90 9 87.0)\">Distance</text></svg>"
        }
      ],
      "answer": 2,
      "explanation": "Moving (sloping line), stopped (flat line), then moving again at the same speed (same slope as before). Graph A has a steeper last part. Graph B goes back to the start. Graph D stops at the end."
    },
    {
      "id": "q11",
      "type": "mcq",
      "objective": "8Pf.03",
      "figure": "<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 105 320 110\" width=\"320\" height=\"110\" role=\"img\" aria-label=\"force diagram\" style=\"font-family:Arial,Helvetica,sans-serif\"><defs><marker id=\"fa785fa0\" markerUnits=\"userSpaceOnUse\" markerWidth=\"14\" markerHeight=\"14\" refX=\"11\" refY=\"7\" orient=\"auto\"><path d=\"M0,0 L14,7 L0,14 z\" fill=\"#5a45b8\"/></marker></defs><rect x=\"118.0\" y=\"124.0\" width=\"84\" height=\"72\" fill=\"#cfc6f3\" stroke=\"#1d1b2c\" stroke-width=\"2.5\"/><text x=\"160.0\" y=\"166.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"normal\" fill=\"#1d1b2c\" ></text><line x1=\"204.0\" y1=\"160.0\" x2=\"308.0\" y2=\"160.0\" stroke=\"#5a45b8\" stroke-width=\"4\" marker-end=\"url(#fa785fa0)\"/><text x=\"256.0\" y=\"153.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"bold\" fill=\"#5a45b8\" >push 20 N</text><line x1=\"116.0\" y1=\"160.0\" x2=\"12.0\" y2=\"160.0\" stroke=\"#5a45b8\" stroke-width=\"4\" marker-end=\"url(#fa785fa0)\"/><text x=\"64.0\" y=\"153.0\" font-size=\"14\" text-anchor=\"middle\" font-weight=\"bold\" fill=\"#5a45b8\" >friction 20 N</text></svg>",
      "shuffle": true,
      "prompt": "The diagram shows the horizontal forces on a box. Ignore the forces acting up and down.\n\nWhat will the box do?",
      "options": [
        "Speed up to the right.",
        "Slow down and stop.",
        "Stay at rest or keep moving at the same speed.",
        "Move to the left."
      ],
      "answer": 2,
      "explanation": "The two forces are equal and in opposite directions, so they are balanced. Balanced forces do not change the motion of the box."
    },
    {
      "id": "q12",
      "type": "classify",
      "objective": "8Pf.03",
      "prompt": "Are the forces on each object balanced or unbalanced?",
      "categories": [
        "balanced",
        "unbalanced"
      ],
      "items": [
        {
          "text": "A car travelling at a steady 80 km/h along a straight road",
          "category": 0
        },
        {
          "text": "A bicycle slowing down as the cyclist brakes",
          "category": 1
        },
        {
          "text": "A parachutist speeding up just after jumping from a plane",
          "category": 1
        }
      ],
      "explanation": "A steady speed in a straight line means balanced forces: the driving force equals the resistance. Slowing down or speeding up means the forces are unbalanced."
    },
    {
      "id": "q13",
      "type": "mcq",
      "objective": "8Pf.03",
      "shuffle": true,
      "prompt": "A cyclist pedals with a forward force of 80 N. Air resistance and friction give a backward force of 50 N.\n\nWhat happens to the cyclist's speed?",
      "options": [
        "It stays the same.",
        "It increases.",
        "It decreases.",
        "It drops to zero."
      ],
      "answer": 1,
      "explanation": "The forward force (80 N) is bigger than the backward force (50 N), so the forces are unbalanced. There is a 30 N resultant force forwards, so the cyclist speeds up."
    },
    {
      "id": "q14",
      "type": "mcq",
      "objective": "8Pf.03",
      "shuffle": true,
      "prompt": "A space probe is far from any planet or star. Its engines are switched off and it moves at a steady speed.\n\nWhich statement explains this?",
      "options": [
        "A forward force is keeping it moving.",
        "There is no unbalanced force on it, so its speed does not change.",
        "Its engines must still be pushing it.",
        "There is no gravity, so it will slowly stop."
      ],
      "answer": 1,
      "explanation": "An object only changes speed when there is an unbalanced force on it. With no unbalanced force, it keeps moving at the same speed. A force is not needed to keep it moving."
    }
  ],
  "rubric": {
    "8Pf.01": {
      "Emerging": {
        "descriptor": "Demonstrates limited understanding of how to calculate speed.",
        "feedback": "Often unsure which numbers to use and may add or multiply distance and time.",
        "feedforward": "Learn the rule: speed = distance ÷ time. Try 100 m in 20 s: 100 ÷ 20 = 5 m/s."
      },
      "Developing": {
        "descriptor": "Demonstrates developing understanding of calculating speed.",
        "feedback": "Uses the formula with simple numbers but may forget units or struggle when time is given in minutes.",
        "feedforward": "Change minutes to seconds first (× 60) and always write the unit, such as m/s."
      },
      "Meets Expectations": {
        "descriptor": "Demonstrates an appropriate understanding of calculating and comparing speeds.",
        "feedback": "Calculates speed and converts units, but may think the longest distance means the fastest runner.",
        "feedforward": "Work out every speed before comparing. A shorter distance in a much shorter time can be faster."
      },
      "Secure": {
        "descriptor": "Demonstrates secure understanding and accurate use of the speed formula.",
        "feedback": "Compares speeds and uses repeated results well, but may average two speeds instead of using total distance ÷ total time.",
        "feedforward": "For average speed, add up all the distance and all the time first, then divide."
      },
      "Exceeding": {
        "descriptor": "Demonstrates confident, accurate and flexible use of speed calculations.",
        "feedback": "Calculates, compares and averages speeds accurately and spots anomalous results in data.",
        "feedforward": "Rearrange the formula to find distance or time, for example distance = speed × time, for real journeys."
      }
    },
    "8Pf.02": {
      "Emerging": {
        "descriptor": "Demonstrates limited understanding of distance-time graphs.",
        "feedback": "Often reads a graph as a picture of the path rather than distance changing with time.",
        "feedforward": "Time is along the bottom and distance is up the side. Practise reading one value, such as the distance at 3 minutes."
      },
      "Developing": {
        "descriptor": "Demonstrates developing understanding of reading distance-time graphs.",
        "feedback": "Reads values from a graph but often thinks a flat line means moving at a steady speed.",
        "feedforward": "A flat line means the distance is not changing, so the object is stopped. Mark every flat section."
      },
      "Meets Expectations": {
        "descriptor": "Demonstrates an appropriate understanding of the shapes of distance-time graphs.",
        "feedback": "Knows flat lines show stopping and sloping lines show movement, but may not link steepness to speed.",
        "feedforward": "The steeper the line, the faster the movement. Compare two sections and say which is steeper."
      },
      "Secure": {
        "descriptor": "Demonstrates secure understanding and accurate use of distance-time graphs.",
        "feedback": "Links steepness to speed and calculates speed from a graph, but may mix up lines going away and coming back.",
        "feedforward": "A line sloping down means the distance from the start is getting smaller. Sketch an out-and-back journey."
      },
      "Exceeding": {
        "descriptor": "Demonstrates confident, accurate and flexible use of distance-time graphs.",
        "feedback": "Reads, calculates from and matches graphs to journeys, including stops and returns.",
        "feedforward": "Draw a graph of your own journey with two speeds and a stop, then calculate each speed."
      }
    },
    "8Pf.03": {
      "Emerging": {
        "descriptor": "Demonstrates limited understanding of balanced and unbalanced forces.",
        "feedback": "Often thinks a moving object always needs a bigger forward force, or that forces disappear when it stops.",
        "feedforward": "Draw the arrows on an object. Equal arrows in opposite directions are balanced, so the motion does not change."
      },
      "Developing": {
        "descriptor": "Demonstrates developing understanding of the effects of forces on motion.",
        "feedback": "Knows what balanced forces are but may think a steady speed needs an unbalanced forward force.",
        "feedforward": "For a car at steady speed, the driving force equals the resistance. Draw both arrows the same length."
      },
      "Meets Expectations": {
        "descriptor": "Demonstrates an appropriate understanding of balanced and unbalanced forces.",
        "feedback": "Identifies most balanced and unbalanced situations but may forget that unbalanced forces change speed.",
        "feedforward": "Compare the two forces. If one is bigger, the object speeds up in that direction or slows down."
      },
      "Secure": {
        "descriptor": "Demonstrates secure understanding and accurate use of balanced and unbalanced forces.",
        "feedback": "Predicts the effect of unbalanced forces but may think a force is needed to keep an object moving.",
        "feedforward": "Explain why a probe in space keeps moving: no unbalanced force means no change in speed."
      },
      "Exceeding": {
        "descriptor": "Demonstrates confident, accurate and flexible use of balanced and unbalanced forces.",
        "feedback": "Explains motion with balanced and unbalanced forces, including steady speed with no resultant force.",
        "feedforward": "Use the size of each force to explain a real case, such as a skydiver reaching a steady speed."
      }
    }
  }
}
