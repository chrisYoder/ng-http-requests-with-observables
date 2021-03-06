# [Angular Http Request with Observables](https://www.positronx.io/handle-angular-http-requests-with-observables/)

## Table of Contents


1. [Introduction](#introduction)
2. [Install and Config Angular Project](#install-and-config)
3. [Create Live Search Layout with Bootstrap](#create-live-search-layout)
4. [Import HttpClientModule](#import-httpClientModule)
5. [Handle Angular HTTP Service with Observable](#hanle-angular-http-service-with-observable)
6. [Managing Http Response with Observable and RxJs Operators](#managing-http-responses-with-observable-and-rxjs-operators)
7. [Display Data with Angular Async Pipe](#display-data-with-angular-async-pipe)
8. [Conclusion](#conclusion)


## Introduction
### JS Promises vs RxJS Observables

|JS Promises | RxJs Observables |
| --- | --- |
| Excited in nature | Lazy in nature, require subscription to be invoked |
| Supports single event | Supports many events (from 0 to many values) |
| Is always asynchronous | Can be either synchronous or asynchronous |
| Not cancelable | Are cancelable |


## Install and Config
- Self-explanatory at this point
- Install bootstrap

## Create Live Search Layout with Bootstrap
- Copy and Pasted

## Import HttpClientModule
- Done. 
- I don't know why the author switched to "county" instead of sticking with "Country" (I did not follow him in this madness).

## Managing Http Response with Observable and RxJs Operators
- We will use the following operators

|Operator|Description
|----|----|
|Subject | A unique sort of RxJS Observable that supports a specific value to be multicasted to multiple observers.|
|tap | It's an RxJS pipeable operator which is used to perform side effects such as logging each value emitted by the source Observable |
|switchMap | It's widely used to get the latest value emitted by the observable |
|debounceTime | emits the latest value and helps in delaying the values transmitted by the root Observable for the specified time |
| distinctUntilChanged | Returns an Observable series that carries only distinguished adjacent elements accordin to the key selector and the comparer |

## Handle Angular HTTP Service with Observable

## Display Data with Angular Async Pipe

## Conclusion

