# Типографская раскладка Ильи Бирмана для Ubuntu

Этот репозиторий содержит адаптацию русской и английской [типографской раскладки Ильи Бирмана](http://ilyabirman.ru/projects/typography-layout/) версии 3.4 для Ubuntu.

![Снимок экрана](_keyboard/snapshot.png)

## Фичи раскладки

Эта раскладка позволяет вводить полезные символы, используя правый <kbd>Alt</kbd> (называемый AltGr). Например, чтобы получить знак евро **€**, вам нужно нажать <kbd>AltGr</kbd>+<kbd>У</kbd> в русском варианте или <kbd>AltGr</kbd>+<kbd>E</kbd> в английском. Дополнительный ряд символов доступен при нажатии еще и Shift-а, например <kbd>AltGr</kbd>+<kbd>С</kbd> даст знак копирайта **©**, а <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>С</kbd> даст знак цента **¢**.

Как и оригинал, эта раскладка поддерживает ввод акцентов и ударений через «мёртвые клавиши», но процесс немного отличается от того, как это делается в Windows или на Маке. Например, для ввода буквы **ў**, нужно нажать и отпустить <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>й</kbd>, а затем <kbd>у</kbd>.

## Установка

Откройте терминал и выполните эту команду:

```
sudo apt-get -qq -y install wget && \
wget -q -O /tmp/typo-birman-master.tar.gz https://github.com/neochief/birman-typography-layouts-for-ubuntu/archive/master.tar.gz && \
tar xf /tmp/typo-birman-master.tar.gz -C /tmp && \
/tmp/birman-typography-layouts-for-ubuntu-master/install.sh
/
```

Эта команда установит и включит обе раскладки в системе, активирует клавишу альтернативных символов (правый Alt), а также установит переключение раскладок через Alt+Shift.

**Обязательно перелогиньтесь после установки.**
