

## Hi there, I'm  Aditya (https://srwaditya.github.io/) <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Hi.gif" width=35 height=35>

<p>
  <em>
    A <b>student</b> <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Medal.gif" width=20 height=20> and a passionate self-taught <b>programmer</b> <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25> from Banaglore, India.
  </em>
 </p>

<img align="right" alt="Coder GIF" height=250 width=350 src="https://i.pinimg.com/originals/e4/26/70/e426702edf874b181aced1e2fa5c6cde.gif" />

<em> Want to know more about me? [Click here](https://srwaditya.github.io/) </em>
<em>



**Here About my Self***

- 👨🏾‍💻 I am a Senior Software Engineer  in CGI. 
- 🔭 I’m interested are Web Developement💻& Data Analysis & Data Scientist📊- , Cricket🏏🌱 , Travling 🛣
- 💻 I am currently doing my MS in Data Science from Liver Pool John Mooore University from Liverpool(Online full time)
- 👯 I’m looking to  work as freelenser for any Data Scince Project ...
- 💬 Ask me about anything, I am happy to help..
- 📫 How to reach me: srw.aditya@gmail.com
- 😄 Pronouns: nothing  
- ⚡ Fun fact: Your highest blood flow is in your kidneys


### GitHub Stats
  
  

{
  "__inputs": [
    {
      "name": "prometheus",
      "label": "Prometheus",
      "description": "Standard Prometheus datasource",
      "type": "datasource",
      "pluginId": "prometheus",
      "pluginName": "Prometheus"
    }
  ],
  "__requires": [
    {
      "type": "panel",
      "id": "graph",
      "name": "Graph",
      "version": ""
    },
    {
      "type": "grafana",
      "id": "grafana",
      "name": "Grafana",
      "version": "4.0.2"
    },
    {
      "type": "datasource",
      "id": "prometheus",
      "name": "Prometheus",
      "version": "1.0.0"
    }
  ],
  "id": null,
  "title": "GitHub Stats",
  "tags": [],
  "style": "dark",
  "timezone": "browser",
  "editable": true,
  "sharedCrosshair": false,
  "hideControls": false,
  "time": {
    "from": "now-3h",
    "to": "now"
  },
  "timepicker": {
    "refresh_intervals": [
      "5s",
      "10s",
      "30s",
      "1m",
      "5m",
      "15m",
      "30m",
      "1h",
      "2h",
      "1d"
    ],
    "time_options": [
      "5m",
      "15m",
      "1h",
      "6h",
      "12h",
      "24h",
      "2d",
      "7d",
      "30d"
    ]
  },
  "templating": {
    "list": []
  },
  "annotations": {
    "list": []
  },
  "schemaVersion": 13,
  "version": 6,
  "links": [],
  "gnetId": 1559,
  "rows": [
    {
      "title": "Dashboard Row",
      "panels": [
        {
          "aliasColors": {
            "stars": "#1F78C1"
          },
          "bars": false,
          "datasource": "prometheus",
          "editable": true,
          "error": false,
          "fill": 1,
          "id": 1,
          "legend": {
            "avg": false,
            "current": true,
            "max": false,
            "min": false,
            "show": true,
            "total": false,
            "values": true
          },
          "lines": true,
          "linewidth": 1,
          "links": [],
          "nullPointMode": "connected",
          "percentage": false,
          "pointradius": 5,
          "points": true,
          "renderer": "flot",
          "seriesOverrides": [
            {
              "alias": "stars",
              "yaxis": 1
            }
          ],
          "span": 4,
          "stack": false,
          "steppedLine": false,
          "targets": [
            {
              "expr": "github_repo_stars{repo=\"docker\"}",
              "interval": "5m",
              "intervalFactor": 2,
              "legendFormat": "{{stars}}",
              "metric": "github_repo_stars",
              "refId": "A",
              "step": 600
            }
          ],
          "thresholds": [],
          "timeFrom": null,
          "timeShift": null,
          "title": "Docker Stars",
          "tooltip": {
            "msResolution": false,
            "shared": true,
            "sort": 0,
            "value_type": "individual"
          },
          "type": "graph",
          "xaxis": {
            "mode": "time",
            "name": null,
            "show": true,
            "values": []
          },
          "yaxes": [
            {
              "format": "short",
              "label": "",
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            },
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            }
          ]
        },
        {
          "aliasColors": {
            "Docker Open Issues": "#C15C17",
            "Open Issues": "#C15C17"
          },
          "bars": false,
          "datasource": "prometheus",
          "editable": true,
          "error": false,
          "fill": 4,
          "id": 2,
          "legend": {
            "avg": false,
            "current": true,
            "max": false,
            "min": false,
            "show": true,
            "total": false,
            "values": true
          },
          "lines": true,
          "linewidth": 1,
          "links": [],
          "nullPointMode": "connected",
          "percentage": false,
          "pointradius": 5,
          "points": true,
          "renderer": "flot",
          "seriesOverrides": [],
          "span": 4,
          "stack": false,
          "steppedLine": false,
          "targets": [
            {
              "expr": "github_repo_open_issues{repo=\"docker\"}",
              "interval": "5m",
              "intervalFactor": 2,
              "legendFormat": "{{Open Issues}}",
              "metric": "github_repo_open_issues",
              "refId": "A",
              "step": 600
            }
          ],
          "thresholds": [],
          "timeFrom": null,
          "timeShift": null,
          "title": "Docker Open Issues",
          "tooltip": {
            "msResolution": false,
            "shared": true,
            "sort": 0,
            "value_type": "individual"
          },
          "type": "graph",
          "xaxis": {
            "mode": "time",
            "name": null,
            "show": true,
            "values": []
          },
          "yaxes": [
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            },
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            }
          ],
          "decimals": null
        },
        {
          "aliasColors": {
            "Forks": "#F9BA8F"
          },
          "bars": false,
          "datasource": "prometheus",
          "editable": true,
          "error": false,
          "fill": 1,
          "id": 3,
          "legend": {
            "avg": false,
            "current": true,
            "max": false,
            "min": false,
            "show": true,
            "total": false,
            "values": true
          },
          "lines": true,
          "linewidth": 1,
          "links": [],
          "nullPointMode": "connected",
          "percentage": false,
          "pointradius": 5,
          "points": true,
          "renderer": "flot",
          "seriesOverrides": [],
          "span": 4,
          "stack": false,
          "steppedLine": false,
          "targets": [
            {
              "expr": "github_repo_forks{repo=\"docker\"}",
              "interval": "5m",
              "intervalFactor": 2,
              "legendFormat": "{{Forks}}",
              "metric": "github_repo_forks",
              "refId": "A",
              "step": 600
            }
          ],
          "thresholds": [],
          "timeFrom": null,
          "timeShift": null,
          "title": "Docker Forks",
          "tooltip": {
            "msResolution": false,
            "shared": true,
            "sort": 0,
            "value_type": "individual"
          },
          "type": "graph",
          "xaxis": {
            "mode": "time",
            "name": null,
            "show": true,
            "values": []
          },
          "yaxes": [
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            },
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            }
          ],
          "decimals": null
        }
      ],
      "showTitle": false,
      "titleSize": "h6",
      "height": "250px",
      "repeat": null,
      "repeatRowId": null,
      "repeatIteration": null,
      "collapse": false
    },
    {
      "title": "Dashboard Row",
      "panels": [
        {
          "aliasColors": {
            "stars": "#E5A8E2"
          },
          "bars": false,
          "datasource": "prometheus",
          "decimals": 3,
          "editable": true,
          "error": false,
          "fill": 1,
          "id": 4,
          "legend": {
            "avg": false,
            "current": true,
            "hideEmpty": false,
            "hideZero": false,
            "max": false,
            "min": false,
            "show": true,
            "total": false,
            "values": true
          },
          "lines": true,
          "linewidth": 1,
          "links": [],
          "nullPointMode": "connected",
          "percentage": false,
          "pointradius": 5,
          "points": true,
          "renderer": "flot",
          "seriesOverrides": [
            {
              "alias": "stars",
              "yaxis": 1
            }
          ],
          "span": 4,
          "stack": false,
          "steppedLine": false,
          "targets": [
            {
              "expr": "github_repo_stars{repo=\"freeCodeCamp\"}",
              "interval": "5m",
              "intervalFactor": 2,
              "legendFormat": "{{stars}}",
              "metric": "github_repo_stars",
              "refId": "A",
              "step": 600
            }
          ],
          "thresholds": [],
          "timeFrom": null,
          "timeShift": null,
          "title": "freeCodeCamp Stars",
          "tooltip": {
            "msResolution": false,
            "shared": true,
            "sort": 0,
            "value_type": "individual"
          },
          "type": "graph",
          "xaxis": {
            "mode": "time",
            "name": null,
            "show": true,
            "values": []
          },
          "yaxes": [
            {
              "format": "short",
              "label": "",
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            },
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            }
          ]
        },
        {
          "aliasColors": {
            "Docker Open Issues": "#C15C17",
            "Open Issues": "#BF1B00"
          },
          "bars": false,
          "datasource": "prometheus",
          "editable": true,
          "error": false,
          "fill": 3,
          "id": 5,
          "legend": {
            "avg": false,
            "current": true,
            "max": false,
            "min": false,
            "show": true,
            "total": false,
            "values": true
          },
          "lines": true,
          "linewidth": 1,
          "links": [],
          "nullPointMode": "connected",
          "percentage": false,
          "pointradius": 3,
          "points": true,
          "renderer": "flot",
          "seriesOverrides": [],
          "span": 4,
          "stack": false,
          "steppedLine": false,
          "targets": [
            {
              "expr": "github_repo_open_issues{repo=\"freeCodeCamp\"}",
              "interval": "5m",
              "intervalFactor": 2,
              "legendFormat": "{{Open Issues}}",
              "metric": "github_repo_open_issues",
              "refId": "A",
              "step": 600
            }
          ],
          "thresholds": [],
          "timeFrom": null,
          "timeShift": null,
          "title": "freeCodeCamp Open Issues",
          "tooltip": {
            "msResolution": false,
            "shared": true,
            "sort": 0,
            "value_type": "individual"
          },
          "type": "graph",
          "xaxis": {
            "mode": "time",
            "name": null,
            "show": true,
            "values": []
          },
          "yaxes": [
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            },
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            }
          ],
          "decimals": -1
        },
        {
          "aliasColors": {
            "Forks": "#F9BA8F"
          },
          "bars": false,
          "datasource": "prometheus",
          "decimals": 3,
          "editable": true,
          "error": false,
          "fill": 1,
          "id": 6,
          "legend": {
            "avg": false,
            "current": true,
            "max": false,
            "min": false,
            "show": true,
            "total": false,
            "values": true
          },
          "lines": true,
          "linewidth": 1,
          "links": [],
          "nullPointMode": "connected",
          "percentage": false,
          "pointradius": 5,
          "points": true,
          "renderer": "flot",
          "seriesOverrides": [],
          "span": 4,
          "stack": false,
          "steppedLine": false,
          "targets": [
            {
              "expr": "github_repo_forks{repo=\"freeCodeCamp\"}",
              "interval": "5m",
              "intervalFactor": 2,
              "legendFormat": "{{Forks}}",
              "metric": "github_repo_forks",
              "refId": "A",
              "step": 600
            }
          ],
          "thresholds": [],
          "timeFrom": null,
          "timeShift": null,
          "title": "FreecodeCamp Forks",
          "tooltip": {
            "msResolution": false,
            "shared": true,
            "sort": 0,
            "value_type": "individual"
          },
          "type": "graph",
          "xaxis": {
            "mode": "time",
            "name": null,
            "show": true,
            "values": []
          },
          "yaxes": [
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            },
            {
              "format": "short",
              "label": null,
              "logBase": 1,
              "max": null,
              "min": null,
              "show": true
            }
          ]
        }
      ],
      "showTitle": false,
      "titleSize": "h6",
      "height": 250,
      "repeat": null,
      "repeatRowId": null,
      "repeatIteration": null,
      "collapse": false
    }
  ],
  "description": "A docker stack which uses Grafana to collect GitHub statistics for selected Repositories"
}
 
 
 
### Top Languages

<p align="center">
<a href = "https://github.com/srwaditya">
  <img src="https://github-readme-stats-aj8vj7k8x.vercel.app/api/top-langs/?username=srwaditya&layout=compact&title_color=ffc857&icon_color=8ac926&text_color=daf7dc&bg_color=151515&card_width=400">
  
</a>
</p>


### Worked Skills

<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" title="python"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" title="javascript"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" title="html5"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jquery/jquery-plain-wordmark.svg" title="jquery"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" title="css3"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg" title="typescript"></code>
<code><img height="40" src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" title="flask"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" title="react"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" title="mongodb"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" title="django"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" title="git"></code>
<code><img height="40" src="https://cdn.worldvectorlogo.com/logos/aws-rds.svg" title="aws-rds"></code>
<code><img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" title="linux"></code>
<code><img height="40" src="https://cdn.worldvectorlogo.com/logos/aws-lambda-1.svg" title="aws-lambda"></code>
<code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/scikit-learn/scikit-learn.png" title="sklearn"></code>

### Follow Me On Social Networking Site

[![Linkedin Badge](https://img.shields.io/badge/-srwaditya-blue?style=flat-circle&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/aditya-shrivastava-836915161/)](https://www.linkedin.com/in/aditya-shrivastava-836915161/) [![Instagram Badge](https://img.shields.io/badge/-@aditya.srw-e02c73?style=flat-circle&labelColor=e02c73&logo=Instagram&logoColor=white&link=https://www.instagram.com/aditya.srw/)](https://www.instagram.com/aditya.srw/)
[![Twitter Badge](https://img.shields.io/badge/-@srwaditya-1ca0f1?style=flat-circle&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/srwaditya)](https://twitter.com/srwaditya/)[![GitHub Badge](https://img.shields.io/badge/-@srwaditya-24292e?style=flat-circle&labelColor=24292e&logo=github&logoColor=white&link=https://srwaditya.github.io/)](https://srwaditya.github.io/) [![Gmail Badge](https://img.shields.io/badge/-@aditya-d54b3d?style=flat-circle&labelColor=d54b3d&logo=gmail&logoColor=white&link=mailto:srw.aditya@gmail.com)](mailto:srw.aditya@gmail.com)
