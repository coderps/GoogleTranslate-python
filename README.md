# GoogleTranslate-python

This is a simple code to translate any language to the desired language text that exists in the Google Translate database, using python 3.x

## Installation

```bash
pip install googletrans
```

## Usage

```bash
>>>from googletrans import Translator
>>> translator = Translator()
>>> translator.translate('안녕하세요.')
# <Translated src=ko dest=en text=Good evening. pronunciation=Good evening.>
>>> translator.translate('안녕하세요.', dest='ja')
# <Translated src=ko dest=ja text=こんにちは。 pronunciation=Kon'nichiwa.>
>>> translator.translate('veritas lux mea', src='la')
# <Translated src=la dest=en text=The truth is my light pronunciation=The truth is my light>
```

For a detailed documentation, go to this [page](https://pypi.org/project/googletrans/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
