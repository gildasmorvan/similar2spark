# similar2spark

An Apache spark based engine for Similar. This engine allows to distribute the execution of a simulation on a cluster. 

## How to use it

Simply use this engine to run a simulation model.

```
ISimulationEngine engine = new SparkEngineDefaultdisambiguation( "spark://master:7077" );
engine.runNewSimulation( simulationModel );
```
