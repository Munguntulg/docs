# Mintlify эхлэлийн багц

Энэхүү эхлэлийн багцыг ашигласнаар таны баримтжуулалтыг (docs) байршуулж, өөрийн хэрэгцээнд тохируулан бэлэн болгох боломжтой.

Энэхүү репозиторийн дээд талд байрлах ногоон **Use this template** товчийг дарж Mintlify эхлэлийн багцыг хуулж авна уу. Багц нь дараах жишээ хуудаснуудыг агуулсан:

- Зааварчилгааны хуудас
- Навигаци
- Тохиргоо, кастомизаци
- API лавлах хуудас
- Түгээмэл компонентүүдийн жишээ ашиглалт

**[Бүрэн Quickstart гарын авлагыг дагана уу](https://starter.mintlify.com/quickstart)**

## Photoshop хичээлүүд

Энэхүү репозиторт дараах Photoshop хичээлүүд багтсан бөгөөд та `tutorials/` болон `ai-tools/` хавтсуудаас олж үзнэ:

- `tutorials/photoshop.mdx` — Photoshop ерөнхий танилцуулга
- `tutorials/photoshop-workspace-overview.mdx` — Workspace танилцуулга
- `tutorials/photoshop-adjustment-layers.mdx` — Adjustment layers
- `tutorials/photoshop-layers-masks.mdx` — Layers & Masks заавар
- `tutorials/photoshop-keyboard-shortcuts.mdx` — Keyboard shortcuts
- `tutorials/photoshop-export-file-formats.mdx` — Export болон файлын формат
- `ai-tools/photoshop-plugins-integrations.mdx` — Plugins болон интеграци
- `ai-tools/photoshop-generative-ai.mdx` — Generative AI ашиглалт
- `tutorials/photoshop-technical-requirements.mdx` — Техник шаардлага
- `tutorials/photoshop-troubleshoot-performance.mdx` — Гүйцэтгэлийн алдааг засах
- `tutorials/photoshop-whats-new.mdx` — Шинэ боломжууд

Эдгээр хичээлүүдийг уншиж, баримтжууллын навигацаас шууд нэвтрэх боломжтой.

## Хөгжил (Development)

Баримтжуулалтынхаа өөрчлөлтийг орон нутгийн орчинд урьдчилж харахын тулд [Mintlify CLI](https://www.npmjs.com/package/mint)-г суулгана уу. Суулгах команд:

```
npm i -g mint
```

`docs.json` файлт байрласан баримтжууллын үндсэн фолдерт доорх командыг ажиллуулна:

```
mint dev
```

Орон нутгийн урьдчилсан харах хаяг: `http://localhost:3000`.

## Өөрчлөлтүүдийг нийтлэх (Publishing changes)

Өөрчлөлтүүдийг репозитор-аас таны байршуулалтад дамжуулахын тулд манай GitHub апп-ыг таны [dashboard](https://dashboard.mintlify.com/settings/organization/github-app)-аас суулгана уу. Өөрчлөлтүүдийг үндсэн (default) салбарт түлхсэний дараа автомат нэгжээр production руу байршуулна.

## Тусламж хэрэгтэй юу?

### Асуудал шийдвэрлэх (Troubleshooting)

- Хэрэв dev орчин ажиллахгүй байвал: CLI-гийн хамгийн сүүлийн хувилбарыг авч байх `mint update` командыг ажиллуулна уу.
- Хэрэв хуудас 404 гарвал: Та `docs.json` файл зөв байрласан фолдерт ажиллуулж байгаагаа шалгаарай.

### Эх сурвалж
- [Mintlify баримтжуулалт](https://mintlify.com/docs)
# test
