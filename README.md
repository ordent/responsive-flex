# \<responsive-flex\>

A set of helper that easily help you to create better flex element. It was designed to be as easy to use as bootstrap.

### Availability

#### Row and Stack
Row is the main element of the flex with horizontal axis.
    <div class="row"></div>

Meanwhile you will need stack to get the vertical axis.
    <div class="stack"></div>

You can also use reverse to get the reverse effect of flex.
    <div class="row reverse"></div>
    <div class="stack reverse"></div>

##### Spacing
Space is the gap between each flex item, you can use these class to have each of the flex spacing effect.

###### Row and Stack - Spacing : Justify Space Around
    <div class="row space-around"></div>
###### Row and Stack - Spacing : Justify Space Between
    <div class="row space-between"></div>
###### Row and Stack - Spacing : Justify Flex Start
    <div class="row space-start"></div>
###### Row and Stack - Spacing : Justify Flex End
    <div class="row space-end"></div>
###### Row and Stack - Spacing : Justify Flex Center
    <div class="row space-center"></div>

#### Container
Giving the proper containing element for the content.
    <div class="container"></div>
##### Container - Width
The default width for container is 80% of its wrapper, if you want to have different width, you can use a width class such as :
###### Container - Width : 50%
    <div class="container width-50"></div>
###### Container - Width : 60%
    <div class="container width-60"></div>
###### Container - Width : 70%
    <div class="container width-70"></div>
###### Container - Width : 80%
    <div class="container width-80"></div>
###### Container - Width : 90%
    <div class="container width-90"></div>
###### Container - Width : 100%
    <div class="container width-100"></div>

#### Item
The flex item that you will use will be based on 12 grid system with calculation based on screen size. There are four media breakpoint exist.
    <div class="responsive-sm-1"></div>
    <div class="responsive-md-1"></div>
    <div class="responsive-lg-1"></div>
    <div class="responsive-xl-1"></div>

#### Offset
Offset is how you could shift the position of the flex item, higher value means the item will be shifted farther. The value will be based on 12 grid system
    <div class="row">
        <div class="responsive-sm-1 offset-1"></div>
    </div>

#### Hidden
Hidden can be used to hide a section in certain screen. Example: Code below will let you hide the section when users open your application in small devices.
    <div class="row">
        <div class="responsive-lg-12 hidden-sm"></div>
    </div>

#### Padding and Gutter
If you needed, padding and flex-item could be arranged to have padding and gutter. Use padded class to make the item have padding, and use gutter class to make the item have gutter. The value inserted will be the value of padding in pixel. Meanwhile if you use gutter, the value will be divided by 2 and implemented as padding and margin of that particular item.

 <div class="row">
        <div class="responsive-sm-1 offset-1 padded gutter"></div>
    </div>