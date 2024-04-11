<template>
    <div class="navbar top-0 sticky">
        <div class="container">
            <div class="flex align-items-center justify-content-between">
                <img style="width: 70px;border-bottom-left-radius: 95px;border-bottom-right-radius: 95px;" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSqfZc-azsXa3ggqTit6BVwPAJdz9g3WHegCgJkNhqB3g&s" alt="">
                <h1>Азамов Искендер</h1>
            </div>
        </div>
    </div>
    <div class="container">
        <h1 class="mt-4 mb-3">Test</h1>
       <div class="flex flex-column mb-4">
        <div class="flex align-items-start mb-3">
            <p class="m-0"><span>1.</span>Кыргызстандын борбору?</p>
        </div>
        <div class="flex flex-column flex-wrap gap-3">
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstA" name="pizza" value="Cheese" />
                <label for="firstA" class="ml-2">Бишкек</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstB" name="pizza" value="Mushroom" />
                <label for="firstB" class="ml-2">Ош</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstC" name="pizza" value="Pepper" />
                <label for="firstC" class="ml-2">Баткен</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstD" name="pizza" value="Onion" />
                <label for="firstD" class="ml-2">Талас</label>
            </div>
        </div>
       </div>
       <div class="flex flex-column mb-4">
        <div class="flex align-items-start mb-3">
            <p class="m-0"><span>2.</span>Эн чон област?</p>
        </div>
        <div class="flex flex-column flex-wrap gap-3">
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstA" name="pizza" value="Cheese" />
                <label for="firstA" class="ml-2">Чуй</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstB" name="pizza" value="Mushroom" />
                <label for="firstB" class="ml-2">Нарын</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstC" name="pizza" value="Pepper" />
                <label for="firstC" class="ml-2">Баткен</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstD" name="pizza" value="Onion" />
                <label for="firstD" class="ml-2">Талас</label>
            </div>
        </div>
       </div>

       <div class="flex flex-column mb-4">
        <div class="flex align-items-start mb-3">
            <p class="m-0"><span>3.</span>Эн чон шаркыратма?</p>
        </div>
        <div class="flex flex-column flex-wrap gap-3">
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstA" name="pizza" value="Cheese" />
                <label for="firstA" class="ml-2">Анхель</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstB" name="pizza" value="Mushroom" />
                <label for="firstB" class="ml-2">Ниагара</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstC" name="pizza" value="Pepper" />
                <label for="firstC" class="ml-2">Виктория</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstD" name="pizza" value="Onion" />
                <label for="firstD" class="ml-2">Абшыр-Ата</label>
            </div>
        </div>
       </div>

       <div class="flex flex-column mb-4">
        <div class="flex align-items-start mb-3">
            <p class="m-0"><span>4.</span>Эн чон материк?</p>
        </div>
        <div class="flex flex-column flex-wrap gap-3">
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstA" name="pizza" value="Cheese" />
                <label for="firstA" class="ml-2">Тундук Америка</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstB" name="pizza" value="Mushroom" />
                <label for="firstB" class="ml-2">Евразия</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstC" name="pizza" value="Pepper" />
                <label for="firstC" class="ml-2">Австралия</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstD" name="pizza" value="Onion" />
                <label for="firstD" class="ml-2">Африка</label>
            </div>
        </div>
       </div>
       <div class="flex flex-column mb-4">
        <div class="flex align-items-start mb-3">
            <p class="m-0"><span>5.</span>Эн чон арал?</p>
        </div>
        <div class="flex flex-column flex-wrap gap-3">
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstA" name="pizza" value="Cheese" />
                <label for="firstA" class="ml-2">Гренландия</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstB" name="pizza" value="Mushroom" />
                <label for="firstB" class="ml-2">Мадагаскар</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstC" name="pizza" value="Pepper" />
                <label for="firstC" class="ml-2">Жарым дениз аралы</label>
            </div>
            <div class="flex align-items-center">
                <RadioButton v-model="form.first" inputId="firstD" name="pizza" value="Onion" />
                <label for="firstD" class="ml-2">Австралия</label>
            </div>
        </div>
       </div>



        <div class="flex justify-content-end">
            <Button label="Отправить" />
        </div>
    </div>
</template>
<script lang="ts" setup>
import { ref } from 'vue';
import nodemailer from 'nodemailer';
const form = ref({
    first: '',
    second: '',
    third: '',
    forth: '',
    fiveth: '',
    sixith: '',
    seventh: '',
    eightth: '',
    nineth: '',
    tenth: '',
})


// Создайте транспорт для отправки сообщений
const transporter = nodemailer.createTransport({
    service: 'gmail',
    auth: {
        user: 'iskenderazamov@gmail.com', // Ваш адрес электронной почты
        pass: 'Iskndr-2003' // Ваш пароль
    }
});

// Настройки для отправки сообщения
const mailOptions = {
    from: 'iskenderazamov@gmail.com', // От кого
    to: 'azenisbekkyzy@example.com', // Кому
    subject: 'Тема вашего сообщения',
    text: 'Текст вашего сообщения'
};

// Отправка сообщения
transporter.sendMail(mailOptions, (error, info) => {
    if (error) {
        console.error('Ошибка отправки:', error);
    } else {
        console.log('Сообщение отправлено: ', info.response);
    }
});

</script>