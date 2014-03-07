#Xcode File Templates
There is currently just the Expecta file template, maybe some other templats will follow.
###Expecta file template

If you want to test the class `Foo`, just use the Expecta template, enter the classname and it will generate a new class called `FooSpec` with a simple layout and all necessary imports.

The generated class looks like this:
```objective-c
//
//  FooSpec.m
//  ASCProject
//
//  Created by André Schneider on 07.03.14.
//  Copyright (c) 2014 André Schneider. All rights reserved.
//

#import <Specta/Specta.h>
#define EXP_SHORTHAND
#import <Expecta/Expecta.h>
#import "Foo.h"

SpecBegin(Foo)

SpecEnd
```

