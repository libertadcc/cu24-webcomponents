npm create vite@latest nombre-del-proyecto -- --template react-ts

npm install @arcgis/map-components-react

// Carga los web components de mapas
import "@arcgis/map-components/dist/components/arcgis-map";
// Transforma el web component de arcgis-map en un component de React
import { ArcgisMap } from "@arcgis/map-components-react";

      <div id="divMap">
        <ArcgisMap
          itemId="5979fd0343d840209d2cd136f5d9aa3e"
          basemap="dark-gray-vector"
        >
        </ArcgisMap>
      </div>


      
#divMap {
  height: 500px;
}

