# Git və GitHub Praktiki Tapşırıq

Bu layihə Git versiya idarəetmə sistemi və GitHub platforması üzrə praktiki tapşırığın icrası məqsədilə hazırlanmışdır.

---

## Tələbə Məlumatları
- **Ad və Soyad:** [Ad Soyad]
- **Qrup:** [Qrup]
- **Layihə qovluğu / Repo adı:** `git-task-ad-soyad`

---

## Layihənin Qısa İzahı
Bu layihə çərçivəsində Git-in əsas iş prinsipləri tətbiq olunmuşdur:
- Lokal Git repository başladılmış və ilkin commit icra edilmişdir.
- Müxtəlif funksionallıqlar üçün fərdi branch-lər (`feature-html` və `feature-python`) açılmışdır.
- HTML və Python faylları üzərində tələb olunan dəyişikliklər edilib hər branch üzrə ayrıca commit-lər yaradılmışdır.
- Bütün branch-lər uğurla `main` branch-i ilə birləşdirilmişdir (merge).
- Commit tarixçəsi və branch strukturu tam şəkildə formalaşdırılmışdır.

---

## Layihədə Olan Fayllar
- **`index.html`** — Tələbə haqqında məlumatları, təqdimatı, maraq sahələrini və keçid linklərini ehtiva edən, sadə CSS stilləri ilə dizayn edilmiş HTML səhifəsi.
- **`app.py`** — İstifadəçidən ad və yaş məlumatlarını daxil etməsini istəyən və nəticəni ekrana çıxaran Python proqramı.
- **`README.md`** — Layihənin təsviri, fayl strukturu və istifadə edilmiş Git komandaları haqqında ətraflı məlumat sənədi.

---

## İstifadə Edilən Əsas Git Komandaları

| Komanda | İzahı |
| :--- | :--- |
| `git init` | Yeni lokal Git repository-si yaradır. |
| `git status` | Faylların və dəyişikliklərin cari vəziyyətini (untracked, modified, staged) göstərir. |
| `git add <fayl>` və ya `git add .` | Dəyişiklikləri staging sahəsinə (commit-ə hazırlıq mərhələsinə) əlavə edir. |
| `git commit -m "mesaj"` | Staging sahəsindəki dəyişiklikləri aydın mesajla tarixçəyə commit edir. |
| `git log --oneline` | Commit tarixçəsini qısa və oxunaqlı şəkildə göstərir. |
| `git branch` | Mövcud branch-lərin siyahısını göstərir. |
| `git switch -c <branch>` | Yeni branch yaradır və dərhal həmin branch-ə keçid edir. |
| `git switch <branch>` | Mövcud branch-ə keçid edir. |
| `git merge <branch>` | Göstərilən branch-dəki dəyişiklikləri cari aktiv branch ilə birləşdirir. |
| `git remote add origin <URL>` | Lokal repository-ni GitHub-dakı uzaq repository ilə əlaqələndirir. |
| `git push -u origin <branch>` | Lokal commit-ləri və branch-ləri GitHub repository-sinə göndərir. |
| `git clone <URL>` | GitHub-dakı uzaq repository-nin nüsxəsini lokal kompüterə kopyalayır. |
