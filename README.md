#Twitter Bootstrap plugin to generate pagination automagically.

## How to use this.

you need [Twitter Bootstrap](http://twitter.github.com/bootstrap/).

### Step.1

install `bootstrap-pagination.js` after `bootstrap.js`.

    <script src="js/bootstrap.min.js"></script>
    <script src="js/bootstrap-pagination.min.js"></script>

### Step.2

put empty div element with class `.pagination` .

    <div class="pagenation"></div>

### Step.3

generate pagination in it.

    $('.pagination').pagination({ page: 3, lastPage: 10 });

the result is ...

    <div class="pagination">
      <ul>
        <li><a>«</a></li>
        <li><a>1</a></li>
        <li><a>2</a></li>
        <li class="active"><a>3</a></li>
        <li><a>4</a></li>
        <li><a>5</a></li>
        <li><a>6</a></li>
        <li><a>7</a></li>
        <li><a>»</a></li>
      </ul>
    </div>

#### one more another example.

    $('.pagination').pagination({ page: 10, lastPage: 10 });

the result is ...

    <div class="pagination1 pagination">
      <ul>
        <li><a>«</a></li>
        <li><a>4</a></li>
        <li><a>5</a></li>
        <li><a>6</a></li>
        <li><a>7</a></li>
        <li><a>8</a></li>
        <li><a>9</a></li>
        <li class="active"><a>10</a></li>
        <li class="disabled"><a>»</a></li>
      </ul>
    </div>

## Copyright and License

Copyright (C) 2012 [takumakei](https://github.com/takumakei)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
