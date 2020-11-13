# gdevelop-ext-ya-ads

Расширение для GDevelop (https://gdevelop-app.com/) и SDK Яндекс.Игр (https://yandex.ru/dev/games/doc/dg/sdk/sdk-about.html) для работы с рекламой.

### Функции

  - Полноэкранный блок рекламы
  - Видеореклама с вознаграждением (rewarded video)

### Установка

Yandex SDK подключить в index.html ДО кода игры и проверить, что SDK доступен глобально -> window.ysdk.
```
<!-- Yandex Games SDK -->
<script src="https://yandex.ru/games/sdk/v1"></script>
```

Загрузить файл расширения по ссылке https://raw.githubusercontent.com/achubutkin/gdevelop-ext-ya-ads/main/Extension.json. Открыть проект игры в GDevelop. Перейти к списку расширений в панели проекта (справа), затем перейти к поиску расширений. 

![j](https://raw.githubusercontent.com/achubutkin/gdevelop-ext-ya-ads/main/01.png)

Далее, нажать Импорт расширения. В качестве файла расширения указать загруженный файл. Подтвердить импорт. 

![j](https://raw.githubusercontent.com/achubutkin/gdevelop-ext-ya-ads/main/02.png)

В списке расширений в панели проекта, отобразится расширение YaAds.

![j](https://raw.githubusercontent.com/achubutkin/gdevelop-ext-ya-ads/main/03.png)

В списке событий добавить новое событие и найти расширение YaAds используя поиск по событиям. Описание и схема работы каждого события отображается слева.

![j](https://raw.githubusercontent.com/achubutkin/gdevelop-ext-ya-ads/main/04.png)

License
----
FREE

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
