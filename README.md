# Laravel Zero Downtime Deployment

## In this it shows how to deploy your laravel application to production without zero downtime using Github action.

# To test on local environment

## Setup
 
```
$ git clone https://github.com/dinushchathurya/laravel-deploy-using-github-actions
$ cd laravel-deploy-using-github-actions
$ composer install
```
  - Duplicate and save .env.example as .env and fill in environment variables

### Run The Service
```
$ php artisan serve
```
# To deploy to production 

- Setup LEMP or LAMP stack on your server> If you wanna know how to configure it [refer this.](https://www.youtube.com/channel/UCCZT71rHQ175Du-1tEviVBA)
- Change <code>deployment-config.json</code> according to your server details.
- Then goto <code>Settings->Secrets->New repository secret</code> and create secret Name as <code>Laravel_ENV</code> and paste your <code>.env</code> in value section.
- In here I have use server password but if you need to use SSH key you can use <code>SSH_KEY</code> variable as above step
- Then push changes to Github and goto <code>Action</code> section

## Author
[Dinush Chathurya](https://dinushchathurya.github.io/)

## License

Copyright (c) 2021 <a href="https://dinushchathurya.github.io/">Dinush Chathurya</a> and <a href="https://codingtricks.io/">codingtricks.io</a>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Blog

https://codingtricks.io/

## 

<p ><h2 align="center">Happy<i class="fa fa-heart" style="color:red;"></i> Coding<i class="fa fa-code" style="color:orange;"> </i></h2></p>