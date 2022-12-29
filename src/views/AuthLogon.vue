<template>  
    <div style = "margin-top: 75px">
      <div class="container h-100">
      <div class="row d-flex justify-content-center align-items-center h-100">
        <div class="col-lg-12 col-xl-11">
            <div class="row justify-content-center">
                <div class="col-md-10 col-lg-6 col-xl-5 order-2 order-lg-1">
                  <p class="text-center h3 fw-bold mb-5 mx-1 mx-md-4 mt-4">Авторизация</p>
                  <form>
                    <div class="form-group">
                        <label for="exampleInputEmail">Email адрес</label>
                        <input type="email" class="form-control" id="exampleInputEmail" placeholder="Введите email">
                    </div>
                    <div class="form-group">
                        <label for="exampleInputPassword">Пароль</label>
                        <input type="password" class="form-control" id="exampleInputPassword" placeholder="Пароль">
                    </div>
                    <div class="form-check">
                        <input type="checkbox" class="form-check-input" id="exapmleCheck">
                        <label for="exampleCheck">Я согалашаюсь с условиями <a href="#!">Пользовательского соглашения</a></label>
                    </div>
                    <div class="d-flex justify-content-center mb-3 mb-lg-4">
                        <button class="btn btn-warning btn-lg" type="submit">Войти</button>
                    </div>
                  </form>
                </div>
            </div>
        </div>
      </div>
      </div>
    </div>
</template>