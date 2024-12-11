# frozen_string_literal: true

source "https://rubygems.org"

# 기본적으로 Jekyll을 설치
gem "jekyll", "~> 4.3.2"

# Jekyll 테마 추가 (예: Chirpy 테마를 사용하는 경우)
gem "jekyll-theme-chirpy", "~> 5.0"

# GitHub Pages에서 지원하는 플러그인
gem "jekyll-feed", "~> 0.15"       # RSS 피드 생성
gem "jekyll-seo-tag", "~> 2.8"    # SEO 태그 추가
gem "jekyll-sitemap", "~> 1.4"    # 사이트맵 생성
gem "jekyll-paginate", "~> 1.1"   # 페이지네이션 지원
gem "jekyll-archives", "~> 2.2"   # 카테고리 및 태그 아카이브 생성

# 테스트용 HTML 검증 도구
gem "html-proofer", "~> 5.0", group: :test

# Windows 플랫폼 관련 설정
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 전용 디렉토리 감시 도구
gem "wdm", "~> 0.2.0", platforms: [:mingw, :x64_mingw, :mswin]
