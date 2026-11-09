# Deep Learning Course

<div dir="rtl">

دورهٔ **یادگیری عمیق و شبکه‌های عصبی** به زبان فارسی، برای کسانی که یادگیری ماشین کلاسیک را با scikit-learn گذرانده‌اند و می‌خواهند شبکه‌های عصبی را از پایه بفهمند و بسازند. این دوره ترم چهارم از یک مسیر شش ترمی است و در ۱۶ جلسهٔ ۹۰ دقیقه‌ای، از پرسپترون و پس‌انتشار خطا (پیاده‌سازی‌شده از صفر با NumPy) تا PyTorch، شبکه‌های کانولوشنی و ResNet، یادگیری انتقالی، RNN و LSTM، سازوکار Attention، ساخت Transformer از صفر، Fine-tuning مدل ParsBERT روی متن فارسی و مدل‌های مولد (VAE، GAN و Diffusion) را پوشش می‌دهد. چارچوب دوره **PyTorch** است.

برای هر جلسه سه فایل وجود دارد:

- **نوت‌بوک درس** (پوشهٔ `sessions`): توضیحات کامل، مثال‌های اجراشده و تمرین‌های پایان جلسه
- **پاسخ تمرین‌ها** (پوشهٔ `solutions`): پاسخ پیشنهادی هر تمرین
- **اسلاید** (پوشهٔ `slides`): ارائهٔ پاورپوینت جلسه برای کلاس

## جلسه‌ها

| جلسه | موضوع | درس | پاسخ‌ها | اسلاید |
|---|---|---|---|---|
| ۱ | از یادگیری ماشین تا یادگیری عمیق: Perceptron و MLP | [نوت‌بوک](sessions/Session01_perceptron_and_mlp.ipynb) | [پاسخ تمرین‌ها](solutions/Session01_perceptron_and_mlp_solutions.ipynb) | [اسلاید](slides/Session01_perceptron_and_mlp.pptx) |
| ۲ | پس‌انتشار خطا و گرادیان کاهشی از صفر | [نوت‌بوک](sessions/Session02_backpropagation.ipynb) | [پاسخ تمرین‌ها](solutions/Session02_backpropagation_solutions.ipynb) | [اسلاید](slides/Session02_backpropagation.pptx) |
| ۳ | مبانی PyTorch: تنسور، Autograd و GPU | [نوت‌بوک](sessions/Session03_pytorch_fundamentals.ipynb) | [پاسخ تمرین‌ها](solutions/Session03_pytorch_fundamentals_solutions.ipynb) | [اسلاید](slides/Session03_pytorch_fundamentals.pptx) |
| ۴ | حلقه آموزش استاندارد: nn.Module، DataLoader و Fashion-MNIST | [نوت‌بوک](sessions/Session04_training_loop.ipynb) | [پاسخ تمرین‌ها](solutions/Session04_training_loop_solutions.ipynb) | [اسلاید](slides/Session04_training_loop.pptx) |
| ۵ | بهینه‌سازی: Momentum، Adam، زمان‌بندی نرخ یادگیری و مقداردهی اولیه | [نوت‌بوک](sessions/Session05_optimization.ipynb) | [پاسخ تمرین‌ها](solutions/Session05_optimization_solutions.ipynb) | [اسلاید](slides/Session05_optimization.pptx) |
| ۶ | منظم‌سازی و نرمال‌سازی: Dropout، Weight Decay، BatchNorm و Data Augmentation | [نوت‌بوک](sessions/Session06_regularization_and_normalization.ipynb) | [پاسخ تمرین‌ها](solutions/Session06_regularization_and_normalization_solutions.ipynb) | [اسلاید](slides/Session06_regularization_and_normalization.pptx) |
| ۷ | شبکه‌های عصبی کانولوشنی (CNN) | [نوت‌بوک](sessions/Session07_convolutional_networks.ipynb) | [پاسخ تمرین‌ها](solutions/Session07_convolutional_networks_solutions.ipynb) | [اسلاید](slides/Session07_convolutional_networks.pptx) |
| ۸ | معماری‌های مدرن CNN: از LeNet تا ResNet | [نوت‌بوک](sessions/Session08_modern_cnn_architectures.ipynb) | [پاسخ تمرین‌ها](solutions/Session08_modern_cnn_architectures_solutions.ipynb) | [اسلاید](slides/Session08_modern_cnn_architectures.pptx) |
| ۹ | یادگیری انتقالی (Transfer Learning) و Fine-tuning | [نوت‌بوک](sessions/Session09_transfer_learning.ipynb) | [پاسخ تمرین‌ها](solutions/Session09_transfer_learning_solutions.ipynb) | [اسلاید](slides/Session09_transfer_learning.pptx) |
| ۱۰ | شبکه‌های عصبی بازگشتی (RNN) و داده دنباله‌ای | [نوت‌بوک](sessions/Session10_recurrent_networks.ipynb) | [پاسخ تمرین‌ها](solutions/Session10_recurrent_networks_solutions.ipynb) | [اسلاید](slides/Session10_recurrent_networks.pptx) |
| ۱۱ | LSTM، GRU و Word Embedding برای دسته‌بندی متن | [نوت‌بوک](sessions/Session11_lstm_and_text_classification.ipynb) | [پاسخ تمرین‌ها](solutions/Session11_lstm_and_text_classification_solutions.ipynb) | [اسلاید](slides/Session11_lstm_and_text_classification.pptx) |
| ۱۲ | مدل‌های Sequence-to-Sequence و سازوکار Attention | [نوت‌بوک](sessions/Session12_seq2seq_and_attention.ipynb) | [پاسخ تمرین‌ها](solutions/Session12_seq2seq_and_attention_solutions.ipynb) | [اسلاید](slides/Session12_seq2seq_and_attention.pptx) |
| ۱۳ | Transformer از صفر | [نوت‌بوک](sessions/Session13_transformer_from_scratch.ipynb) | [پاسخ تمرین‌ها](solutions/Session13_transformer_from_scratch_solutions.ipynb) | [اسلاید](slides/Session13_transformer_from_scratch.pptx) |
| ۱۴ | مدل‌های ازپیش‌آموزش‌دیده با Hugging Face: تحلیل احساس متن فارسی با ParsBERT | [نوت‌بوک](sessions/Session14_hugging_face_transformers.ipynb) | [پاسخ تمرین‌ها](solutions/Session14_hugging_face_transformers_solutions.ipynb) | [اسلاید](slides/Session14_hugging_face_transformers.pptx) |
| ۱۵ | Autoencoder و Variational Autoencoder | [نوت‌بوک](sessions/Session15_autoencoders_and_vae.ipynb) | [پاسخ تمرین‌ها](solutions/Session15_autoencoders_and_vae_solutions.ipynb) | [اسلاید](slides/Session15_autoencoders_and_vae.pptx) |
| ۱۶ | مدل‌های مولد: GAN، Diffusion و پروژه پایانی | [نوت‌بوک](sessions/Session16_gans_and_diffusion.ipynb) | [پاسخ تمرین‌ها](solutions/Session16_gans_and_diffusion_solutions.ipynb) | [اسلاید](slides/Session16_gans_and_diffusion.pptx) |

## مسیر یادگیری

| ترم | دوره |
|---|---|
| ۱ | [برنامه‌نویسی پایتون](https://github.com/keyvanmahmoudi/Python_Course) |
| ۲ | [علم داده](https://github.com/keyvanmahmoudi/Data_Science_Course) |
| ۳ | [یادگیری ماشین](https://github.com/keyvanmahmoudi/Machine_Learning_Course) |
| ۴ | **یادگیری عمیق و شبکه‌های عصبی** (همین دوره) |
| ۵ | [مهندسی مدل‌های زبانی بزرگ (LLM) و برنامه‌نویسی با کمک هوش مصنوعی (Vibe Coding)](https://github.com/keyvanmahmoudi/LLM_Engineering_Course) |
| ۶ | [ساخت محصول هوش مصنوعی با FastAPI و کسب درآمد](https://github.com/keyvanmahmoudi/AI_Product_Course) |

مدل‌های زبانی بزرگ، RAG و ساخت Agent در ترم پنجم (مهندسی LLM) آموزش داده می‌شوند.

## اجرا

ساده‌ترین راه، باز کردن نوت‌بوک‌ها در Google Colab با دکمهٔ **Open in Colab** بالای هر نوت‌بوک است. نوت‌بوک‌های جلسه‌های ۳ تا ۹، ۱۱ و ۱۳ تا ۱۶ در Colab به‌طور پیش‌فرض با **GPU** (T4) باز می‌شوند؛ اگر این‌طور نبود، از منوی `Runtime → Change runtime type` گزینهٔ **T4 GPU** را انتخاب کنید. جلسه‌های ۱، ۲، ۱۰ و ۱۲ روی CPU هم در چند دقیقه اجرا می‌شوند. برای اجرا روی سیستم خودتان (برای نصب PyTorch با پشتیبانی GPU، دستور مناسب سیستم خود را از [pytorch.org](https://pytorch.org/get-started/locally/) بگیرید):

</div>

```bash
git clone https://github.com/keyvanmahmoudi/Deep_Learning_Course.git
cd Deep_Learning_Course
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

<div dir="rtl">

## داده‌ها

همهٔ داده‌ها هنگام اجرای نوت‌بوک به‌طور خودکار دانلود می‌شوند و نیازی به دانلود دستی نیست:

| داده | جلسه | منبع |
|---|---|---|
| Fashion-MNIST | ۴ تا ۷، ۱۵ و ۱۶ | `torchvision.datasets` ([Zalando Research](https://github.com/zalandoresearch/fashion-mnist)، مجوز MIT) |
| CIFAR-10 | ۷ و ۸ | `torchvision.datasets` ([Krizhevsky, 2009](https://www.cs.toronto.edu/~kriz/cifar.html)) |
| Oxford Flowers-102 | ۹ | `torchvision.datasets` ([Nilsback & Zisserman, 2008](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)) |
| IMDB | ۱۱ | Hugging Face Hub: [`stanfordnlp/imdb`](https://huggingface.co/datasets/stanfordnlp/imdb) |
| Tiny Shakespeare | ۱۳ | [karpathy/char-rnn](https://github.com/karpathy/char-rnn) (مالکیت عمومی) |
| دیوان حافظ | ۱۳ (تمرین) | [Perseus Digital Library](https://github.com/PerseusDL/canonical-farsiLit) (CC BY-SA) |
| نظرات دیجی‌کالا و اسنپ‌فود | ۱۱ (تمرین) و ۱۴ | Hugging Face Hub: [`hezarai/sentiment-dksf`](https://huggingface.co/datasets/hezarai/sentiment-dksf) |
| Churn Modelling | ۴ (تمرین) | [دورهٔ یادگیری ماشین](https://github.com/keyvanmahmoudi/Machine_Learning_Course/tree/main/data) |
| دمای روزانهٔ ملبورن | ۱۰ (تمرین) | [jbrownlee/Datasets](https://github.com/jbrownlee/Datasets) |

داده‌های مصنوعی (سری زمانی سینوسی، تاریخ‌ها، مارپیچ دوبعدی و ...) در خود نوت‌بوک‌ها ساخته می‌شوند. مدل‌های ازپیش‌آموزش‌دیده (ResNet، EfficientNet، ParsBERT و XLM-RoBERTa) هم از `torchvision` و Hugging Face Hub دانلود می‌شوند.

## فونت‌ها

اسلایدها با فونت **Times New Roman** برای متن انگلیسی، **وزیرمتن (Vazirmatn FD)** برای متن فارسی و **لاله‌زار (Lalezar)** برای تیترها طراحی شده‌اند. قبل از باز کردن اسلایدها، فونت‌های پوشهٔ [`fonts`](fonts) را روی سیستم نصب کنید (هر دو فونت با مجوز آزاد SIL OFL منتشر شده‌اند).

## مدرس

**کیوان محمودی**، دانشجوی دکتری مهندسی کامپیوتر گرایش نرم افزار، دانشگاه تهران
[LinkedIn](https://www.linkedin.com/in/keyvan-mahmoudi-7b3280103) · [Hugging Face](https://huggingface.co/KeyvanMahmoudi)

## مجوز

این مخزن تحت [مجوز MIT](LICENSE) منتشر شده است. مجموعه‌داده‌ها و مدل‌های ازپیش‌آموزش‌دیدهٔ شخص ثالث مجوز خودشان را دارند (جدول بالا).

</div>
