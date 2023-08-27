
# Minacraft Launcher Core Ultimate (MCLCU)

Que es?
MCLCU es una libreria para los launcher de minecraft esta libreria se usa para todo, desde descargar las libreiras asta iniciar el juego, la libreria es opensource i se puede modifica a antojo, la libreria original es esta i esta echa por kender aqui hay una pequeña introducion a como se usa 
<pre>
```java
JsonUtils.readVersions("");
```
</pre>
usa esto para obtener una lista en forma de array con las versiones a poder descargar, en los "" va la url del manifienso generalmente es <pre>'https://launchermeta.mojang.com/mc/game/version_manifest.json'</pre>
<pre>
```java
JsonUtils.ReadFileVersions("", version);
```
</pre>
con esto podemos obtener la ulr del json de la version de igula forma necesitremos introdicir el archivo manifest en los "" i la version en version en forma de string

<pre>
```java
JsonUtils.getJsonVersion(urlManifest);
```
</pre>

