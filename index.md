
<table class="max-width-50">
  <caption>One Data Model Registry</caption>
  <thead>
    <tr class="height-20">
       <th class="width-10">URN</th>
       <th>URL</th>
       <th>Organization</th>
       <th>Tag(s)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://raw.githubusercontent.com/one-data-model/prototype-registry/verification/mjk-examples/BT%20Mesh/sensor.sdf.json">URN</a></td> 
      <td>mesh sensor</td> 
      <td>BT Mesh</td>
      <td>Tag1, Tag5, Tag6</td>      
    </tr>
    <tr>
      <td><a href="https://raw.githubusercontent.com/one-data-model/prototype-registry/verification/mjk-examples/DotDot/Thermostat-odm-v0-2.json">URN</a></td>
      <td>Thermostat</td>
      <td>Dotdot</td>
      <td>Tag4</td>      
    </tr>
    <tr>
      <td><a href="https://raw.githubusercontent.com/one-data-model/prototype-registry/verification/mjk-examples/IPSO/ipso3300-new.sdf.json">URN</a></td> 
      <td>3300</td>
      <td>IPSO</td>
      <td>Tag3</td>
    </tr>    
    <tr> 
      <td><a href="https://raw.githubusercontent.com/one-data-model/prototype-registry/verification/mjk-examples/OCF/ocf-airflowcontrol.sdf.json">URN</a></td> 
      <td>airflowcontrol</td>
      <td>OCF</td> 
      <td>Tag1, Tag2</td>      
    </tr>
    <tr> 
      <td><a href="https://raw.githubusercontent.com/one-data-model/prototype-registry/verification/mjk-examples/OCF/ocf-airflowcontrol.sdf.json">TBD1</a></td> 
      <td>TBD1</td>
      <td>TBD1</td> 
      <td>TBD1</td>      
    </tr>
    <tr> 
      <td><a href="https://raw.githubusercontent.com/one-data-model/prototype-registry/verification/mjk-examples/OCF/ocf-airflowcontrol.sdf.json">TBD2</a></td> 
      <td>TBD2</td>
      <td>TBD2</td> 
      <td>TBD2</td>      
    </tr>     
  </tbody>
</table>


{
  "created": "2019-11-23T00:12:38.483Z",
  "folder": "models",
  "items": [
    {
      "name": "BT_Mesh",
      "items": [
        {
          "name": "sensor.sdf.json",
          "data": {
            "info": {
              "title": "Example file for BT Mesh Sensor Model definition in OneDM SDF format",
              "version": "20190910",
              "copyright": "Copyright 2019 Example Corp. All rights reserved.",
              "license": "http://example.com/license"
            }
          }
        },
        {
          "name": "temperature-sensor.sdf.json",
          "data": {
            "info": {
              "title": "Example file for BT Mesh Sensor Temperature type definition in OneDM SDF format",
              "version": "20190910",
              "copyright": "Copyright 2019 Example Corp. All rights reserved.",
              "license": "http://example.com/license"
            }
          }
        }
      ]
    },
    {
      "name": "DotDot",
      "items": []
    },
    {
      "name": "IPSO",
      "items": [
        {
          "name": "ipso3300-new.sdf.json",
          "data": {
            "info": {
              "title": "Example ODM model for a relatively simple composed thing using\n    IPSO Smart Object Components",
              "version": "20190524",
              "copyright": "no copyright",
              "license": "not licensed"
            }
          }
        },
        {
          "name": "ipso3300.sdf.json",
          "data": {
            "info": {
              "title": "Example ODM model for a relatively simple composed thing using\n    IPSO Smart Object Components",
              "version": "20190524",
              "copyright": "no copyright",
              "license": "not licensed"
            }
          }
        }
      ]
    },
    {
      "name": "OCF",
      "items": [
        {
          "name": "ocf-airflowcontrol.sdf.json",
          "data": {
            "info": {
              "title": "OCF odmObject libarary",
              "version": "20190530",
              "copyright": "OCF (TBD)",
              "license": "OCF (TBD)"
            }
          }
        },
        {
          "name": "ocf-example.sdf.json",
          "data": {
            "info": {
              "title": "Example ODM model to illustrate the use of the odmView class",
              "version": "20190531",
              "copyright": "no copyright",
              "license": "not licensed"
            }
          }
        },
        {
          "name": "ocf.washer-new.sdf.json",
          "data": {
            "info": {
              "title": "OCF washer",
              "version": "20190530",
              "copyright": "OCF (TBD)",
              "license": "OCF (TBD)"
            }
          }
        }
      ]
    },
    {
      "name": "ZCL",
      "items": [
        {
          "name": "level.sdf.json",
          "data": {
            "info": {
              "title": "Example ODM model for the ZCL Level cluster",
              "version": "20190504",
              "copyright": "no copyright",
              "license": "not licensed",
              "validationschema": "http://github.com/one-data-model/language/v1/sdf-schema.json"
            }
          }
        },
        {
          "name": "level.x.sdf.json",
          "data": {
            "info": {
              "title": "Example ODM model for the ZCL Level cluster",
              "version": "20190504",
              "copyright": "no copyright",
              "license": "not licensed"
            }
          }
        }
      ]
    }
  ]
}
