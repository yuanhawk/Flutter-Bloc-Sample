# flutter_bloc_concepts

Flutter Bloc Concepts

## Getting Started

Cubit - subset of the features of bloc<br>
Observes stream of states, emits functions that are not part of a stream

Bloc<br>
Observes stream of states, emits stream of events

BlocProvider provides a single instance of a Bloc (DI)

BlocBuilder - re-builds UI based on bloc state changes -> called multiple times by Flutter engine<br>
Builder function must be pure (return val depend on function arg)

BlocListener - observes state change

BlocConsumer - BlocBuilder + BlocListener

RepositoryProvider provides a single instance of Provider (DI)