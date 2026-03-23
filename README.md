<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>陳小明 - 專業個人特色介紹</title>
    <style>
        /* 基礎樣式 (LinkedIn 藍灰色調) */
        body {
            font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f2ef; /* 淺灰色背景 */
            color: #1a1a1a;
            line-height: 1.5;
        }

        /* 網頁容器 */
        .container {
            max-width: 900px;
            margin: 40px auto;
            background-color: #fff; /* 白色卡片 */
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            overflow: hidden;
            display: flex;
            flex-direction: column;
        }

        /* 區塊樣式 */
        section {
            padding: 24px;
            border-bottom: 1px solid #e0e0e0;
        }

        h1, h2, h3 {
            color: #000;
            margin-top: 0;
        }

        p {
            margin: 10px 0;
        }

        /* 頁首 (LinkedIn Cover/Intro Section) */
        .profile-header {
            position: relative;
            background-color: #0a66c2; /* LinkedIn 藍色 */
            color: #fff;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* 背景圖片 (選填) */
        .profile-background {
            width: 100%;
            height: 150px;
            background-color: #f3f2ef; /* 或更換為 Data URI */
            background-position: center;
            background-size: cover;
        }

        /* 頭像與基本資訊 */
        .profile-info {
            display: flex;
            align-items: flex-start;
            margin-top: -60px; /* 向上移動以覆蓋背景 */
            width: 100%;
            padding: 0 24px 24px;
            box-sizing: border-box;
        }

        /* 圓形頭像 (嵌入 Data URI) */
        .profile-picture-container {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #fff;
            overflow: hidden;
            flex-shrink: 0;
            margin-right: 24px;
        }

        .profile-picture-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .profile-text {
            flex-grow: 1;
        }

        .profile-text h1 {
            font-size: 2.4rem;
            margin-bottom: 5px;
            color: #fff;
        }

        .profile-text .headline {
            font-size: 1.2rem;
            color: #e0e0e0;
            margin-top: 0;
            font-weight: normal;
        }

        .profile-text .contact-info {
            color: #e0e0e0;
            font-size: 0.9rem;
            margin-top: 10px;
        }

        .contact-info a {
            color: #fff;
            text-decoration: none;
            margin-right: 15px;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        /* 關於我 */
        .about-section h2 {
            font-size: 1.6rem;
        }

        /* 工作經歷 */
        .experience-item {
            margin-bottom: 24px;
            display: flex;
            gap: 15px;
        }

        .experience-logo {
            width: 48px;
            height: 48px;
            border-radius: 4px;
            border: 1px solid #e0e0e0;
            background-color: #f3f2ef; /* 預設灰色 logo */
            display: flex;
            justify-content: center;
            align-items: center;
            color: #888;
            font-size: 0.8rem;
            flex-shrink: 0;
        }

        .experience-content {
            flex-grow: 1;
        }

        .experience-content h3 {
            font-size: 1.2rem;
            margin-bottom: 5px;
        }

        .experience-content .company-dates {
            font-size: 0.9rem;
            color: #666;
            margin-bottom: 10px;
        }

        .experience-content ul {
            padding-left: 20px;
            margin-top: 0;
        }

        /* 技能 */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .skills-list li {
            background-color: #e6f3ff;
            color: #0a66c2;
            padding: 8px 16px;
            border-radius: 16px;
            font-size: 0.9rem;
            font-weight: 600;
        }

        /* 專案與學歷 */
        .project-item, .education-item {
            margin-bottom: 20px;
        }

        .education-item h3 {
            font-size: 1.1rem;
            margin-bottom: 3px;
        }

        .education-item p {
            font-size: 0.9rem;
            color: #666;
            margin-top: 0;
        }

        /* 頁尾與額外資訊 */
        .footer {
            background-color: #fff;
            color: #666;
            text-align: center;
            font-size: 0.8rem;
            padding: 10px;
        }

        /* 響應式設計 */
        @media (max-width: 768px) {
            .container {
                margin: 0;
                border-radius: 0;
            }

            .profile-info {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }

            .profile-picture-container {
                margin-right: 0;
                margin-bottom: 15px;
            }

            .profile-text h1 {
                font-size: 2rem;
            }

            .profile-text .headline {
                font-size: 1rem;
            }

            .experience-item {
                flex-direction: column;
                align-items: flex-start;
            }

            .experience-logo {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>

    <div class="container">

        <section class="profile-header">
            <div class="profile-background"></div>
            
            <div class="profile-info">
                <div class="profile-picture-container">
                    <img id="profile-picture" src="data:image/data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEhUTEhMWFhUVFRgVFxUXFRcYFxUVFxcWGBUVFRUYHSggGBolHRYVITEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OGhAQGy0fHSUrLS0tLS0tLS0tLS0tKy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAN0A5QMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAFAQIDBAYHAAj/xABTEAABAgMEBQcEDAsIAAcAAAABAAIDESEEBRIxQVFhcZEGEyIygaGxQlLB0QcUI2JjcpKTorLi8BUkJTNDU1SCwuHjFhdkc7PD0tM0NUR0g6Px/8QAGgEAAwEBAQEAAAAAAAAAAAAAAAEDAgQFBv/EAC0RAAICAQMDAwMDBQEAAAAAAAABAhEDEiExBCJBE1FxMmGxgZHwFCMzQlIF/9oADAMBAAIRAxEAPwBbit8wWkEkGZcTniJMztzR1lo2d6xV1W/CTKFEcTKgwjKet21HYV4xjlZXfvRIY8CUmmIPNjnUE8RTsQRtptRys8MfGtB8BDPipA+2HJlnbvdEd4NCVfcP0DAjbU7GdaDCFbT+kszd0KIfF6X2naznamD4tnHpeil7huGMe1ex7SspbTbGWmDAZagTEa983QWYeiDIForI71eN8WiD/wCJss2j9LZ5xG73Qj029mJDiOw8CnAKndt6wY4nBiMfLMA9JuxzTVp3hXZ/eSyB4BOkkqlltQAoCdJMknBqAFITgUgapAAM06bEeAQ+13s1o6AL3TkBUDfM6EE5WcpzCeIUKWXSJ16tw++SzD+VLpSaZmfSdpJ2av8A9VYwXkTsOXpftqqMYYNTG/xGqoweW1oY2Rk+VMRbWmnahdo5QFzTQA65TMtg170AdaXmU8sUzTPfwCo1EVM6NZOW7HyD5jtR2yWxkQTY4GWfoXIrVEAb7k3pHSdAHpJqiHJXlUGECJMEOkT5zD5LhrBqCsSgnwFtHUiUhcmsdiAIqCJjcUpaVE2NJTSU4tKaWpDGkppKcWppbtTsKEbFc3quI3EjwXkmDavIsDEWHHj6EiZZO7NIRuHeZZ+dhPaPOaMbeLajgglheREEtq1d3worxNoJGuQA4psQ+w3jCifm4jXbARMb25hXgqdruBkT86yGTrqHdjmiY4qGHcMZhHNWmIIZBm1x5wg6MBeJjisPJBctGvTk/AWaE8BCzdEbTaYvZzY/hSfgl2mNaD++PQ1L1cf/AEv3D05ezKttH5Ss+yDFPiFopLGx7vb+EIbC+JLmHuJdEcD1pdakgjrLngnznb4sQ/xKtp8GKrkW87hs0Y4ntDXjKIx2CINz21VBzLXZ/wA3aIdpYPIjkMibhGbQ/vBE23LA/Vg7yT4lSsueAMoMP5ARuGwPsXK6AXBkbFAiGmGJLCT72K0lh4o/j2LO8rbHDbZImFjAZtEw0DN4WkLENCEx7F7HsS4U4NSpjGFxUZH3mp8KTCsuxnJ+Vznm1RGyBrIEaBOv32JLHcpwtIGgntqFp+Vt3jnhEOlo4ih9ClsMKTKDaNxTyTaSotggnyZiDc5ayZHSPiU0XaAJLRx4tCDJUi3CJnKfcp62dSxxoACzSpJAb0s2GIHAZ571prbELiayaqMGxiJEhNNcURrDuJVYPc5sq2On3I0izwQZz5ts+0TVsp0wKDRRNLgpskNITSE4nfwSE7DwQAxwTZJ5nqKbI6vBADSEicZ6u9eTAw93sm8dq6JcLZQBkak03rnl2PlEG4+C6FcP5hu931ip9RJ6WbxJaixajklgdUJtrPV7fQnQOqNy8aT3PQXA5NKckU2xmeiCd6N2WN3+qEbdCadAQUD8qHZYvGMEdVcra0/CMR8/JVjHDKRFdc0znz5w4FMvHrNocj4qFpPmnu9a9bp5SeNNs4sqSmyhytik2eU84kMZe/ajbo5876KAcpp8y0SP56Fq88bUZOLV3hXt0SpEvOnzjwC9zh1u7lGA7UOP8k4NdqHE+pK2A8POt3EJwdv4pga7ZxPqTgx2zvS3AD8o4YeGtqCAXTmagSBCdCs7sIwjQPvtRC13e+JKUujU08mYJnwVZ3Ra1uoLM3tuduFKlRk72scUxOs6YphIlWeetT2uxO9r4dI+8lYvC0OdEDAaTmZUpq7Uy8ryIaWhshoE/EpXdFtNWZyJZS6WdD50vBXrhsP4xDbqeHZ+aZ6VRhx5vBIlSR2ohdtpwWlhqRiltkaelV3OaSVHRCTrTCTr+/BOdCGs8SmGCNvynetYOYQ700jaeK8YLdvE+tIYLdSYCEJpATuabqHAJObbqHAIAiJbs7l5SYBqXkAYa7D0+wro1xD8Xh9v1nLn12CT/wB0+hdGuce4Q/i+kqPVuoFMH1HrYMu30J8AdFu4Jtu8kb/QpoA6Ldw8F40nud/+qGkJJKWSaQsMVmdgj8pxNlkaOMX+SOFBrKPylH2WaEOLiUcIVcvK+EKHn5BlvJxCQ8n0lRtJ1d6kt7umPi+kpGlev03+KJw5vrYJ5RzMOHQVtEHT8INiM9LUOJ9SFcoerB/9zA/1AjAC6CY0YtnE+pPGLZxKUNShoSEIMWzvTgHaxwPrShqcAgZHEY4iWOVZ0GrtQu3CRIJnLTr2oyhF9Nk4HW30lTyK4nT003qoz1sLxEHNyBIzImBJVrfDfKbm1PvqS4IqJaclWt8ZslOEvB2NGSj2dweDlLQNO9aDkxZTFtLXDqw5OcdRHVHHwKovhl8QNZUuIAG9dEum7WQIYYwbXHS52krpbOHI1HZE5YfOPd6kww9p4qcppWSBXdC2niU3mht+U71qdxTC5AyIwht4n1pphDUFKXJrnIAhMJvmjgF5OJXkAYuxP90OhuE0z1Lpd0t9whfEb4Ll9lPS/dPiF1W62+4wv8tn1Qo9f9BrByQ28VG53oViE3ojcPBRXg3L4rvQrbG0G4Lw2+5nc5dqIsKQtU0k0tSMqRnLCPyjatkGCPrFGiEIuz/zC27GWcfQJRpwVcvK+F+BwYBvWNhiS96PEqu22bO9SXx+d/dHpVdj5aCeHrXvdLBejH4ODNLvZXviOSIVMo8I8HhExazq8UNvJ0+aoR7tDzlr2IxDAl/JXUUTctkR+2zqS+3DsUNqkPUBXsCqi1huUwdZEjuVIYdRlzoJttLjkO5L7aOkgb6IFEvEis/vP+alhXlOU6g4gRtFfBVWCBj1Gae53MiPLXOqBMNoMWuRVblNCAcNGzVq7FnrZGwywmTsxsT7NypZGHNWqjx1Ygz7R5Q2iuzSo9Rg7XpOjpsumXcQR4epCre0gI7HhtIo4EaHNND6kGtjSAZlebG06Z6sqatFHk/ahDtLXvEwJjdMSmuhNtbS7CHdKU5GkxrGtcygwZHE6g26lFeHKU84zAaMGGfnVqdy7se73PNzKtzqxKULD2DlSZCR4oxZOU4n02iWsUV/T9jl1GkENPEHcOxNstphvZja6YnKgmQdUhpTvbjNbvknvCzRqyG0WXF5Zb8WYTIUAtaBjnLS4EuPap3Wpmt/yT6lA+3Mn1nT+KdGaKQDC3aOBXk9z968nQHOWukez0hdcu8Shw/iM+qFx60N8PSuw2ejGjU1o7gvN/8AQ+lF8HkhvQ/VKvDLsQ23v6Uve+kq8Xrw67mdkl2oeUwppekxJGUgDc9bdbzts4/+pG3BAbhd+OW8/CQRwhBHHOVc31L4X4NQRmb7tDWxTOeTdGxVId5wxpPBX7xssOJGIc94dSgkG5DIkS061I3k+3XE4M9S+k6aP9mPwjzsslrfyB7wvFjuakT0YrSeicpolCt0AmpHax3qQjlpZPa8KG9hcSYzB0g2WYnkBrRmDd7BAbFcTMtBlhZIk6B0Zy7VaMXbMSapENvjNBk2UpZgSnxqgNutNFavB8szQnPUTrOorNXtayJg/wA9x2rob0qia3Fdbi7EJ5NJnua6vgrNktIwscTTna7sFVl2Wr3R1aFp4ET9au2ONOA3bFZ3g+hY1GqNPCjmI50Q0GTRsGSDR4YeTqBRCPFk2Wk0AVC8Y4htDGjpHPWmwQHtMR7T0Hu45bjmonXnH0vd8pWMNK5qnFCk4plFJrhle0WmI7rOJ3knxTGtknATqlcEhMs2WMQVai20g0OvuCHMMkx0SvFOxUaTkzyniWeJjnNtMTTk7+dc12i7LSHwREaZh+JwMpCRc7QZ+K+cIT1172LL2xwX2dxqwF7PinrDsNe0rl6qcowuJXEle5ti8yCF3va8EidLXjqz0DaEWazojcFWtN3iLRxIk12W0aV5vS9RlnminLY6ckIKL2BH4UFKHL9Wf+xeRdvJqDtO/D6l5e5TOLY5RaG17PSuttNBuXKora8PFdScV53XK4o6Om5ZXtZ6XYB3lWi9UYx6fyfFWC5eM47nocpEuNJjUJckxKbQUBuTzvxm3H4Zg4Qwjhcs5yZd7tbj/iZcGhHS5VzLv/RfgWNbFeNbmnGwz6MhKYlWR17VFdTRjMvvVBLwrGfv9ARfk4zpHQvoMEaxx+EeQ2lkl8sH+yiPcrMNdob4tT7daCWtacmsDZbgJzVjl9Ca51ja6o517pZVY1rh3yQi1RnHqy3mo4TC68KqzE1dFK1RhI1AppHiFkL1jZiU5Za5b9iPXgXj9K8e9wsaDuIb3FZS9Xu0uLt8p+C3JhFAwxKk+9PeJIzZDKHDbrig8GrPz9XejIfVg1TPFSNhyyxcTy45CcuxVwZ4nmpJVq7oYaxzjIyEjpAceqBKjjQ59FSYjJhzJbiaSGtLZHNwGTZVGVdydgVuZAE3SnSc8mjOuskaBoM0Gt8UOd0RIUpu3aUUtDg7ogEjOkhQETe81lk6h6s9SHw21M2dXMdKZM2gN2V3ZkTySsCGBBLiGtEyaD7lSRbPKgcCdlBpyJzorFnwgtZ5zhjIEyBlgbKuRM9ZpKit2sHMsM3CgADXFsmdBrSZ+URRomK1rJAAHlQuKIWlpn0QMp4ZN6OyekznTduVCM2WzYdB1JgRtdXtWm5I3qYEZkQeS6o1tNHDgVlMVVdsMaRWJxUk0xxdH0zCiAsaRUFoIOsSoVBHfqn1XeAWU9j2+eesvNk9OCcO0sMyw+I7FpHOz+K7wXi9LicOqUX/ADY6cyvC5fzkjivdiPSd8opEsTrGhz2Ly9d8k0tjm4HT7W+JXS4hqubw/wA6BrfDH0iujxM1Dq1aQ+ndNlSJ1+0KUlQud0u0eCeSvLyRo7ouxxckxJpKbNc0kUQB5Ku90tx/xb/AI85yznJI9K2HXa4noR5zlXMv7n7fgzj+kGxbbZw9wfIOBkSZjvAV6673s2KXOw21PletQw8zXSUSuQe6FfS4/wDGl9keJJ97+WVL2iNiW6xFrw9ko0pSLQWsqQdJqOARu0BjhJzWkaiAR3rPXhHxW+yE6W2l30WAIq91a5LlnLez0ccKVGc5TWKzlpABaTkJEtJ9HZwXIr2ecZadBlXPtX0RCtLRQSCqXnc9ktIlGgw4m0iThueKjiqRyNc7mJ4k91sfNwz7UZgRCHtcMxI8K6F0m8vYoszzOzxYkI+a73RnfJ3eVnLw5BWuCScIiMHlQuk6XxDIz+81vWmQ9OSIrIQWuwudIzcWhkyKGZqZSAJrPJR42tBc8Vc5uJrwSes4urMFzaAEzbnLake0tYWOmwyJwESIwgmbsiTQiRGTuxDHAua0Gfp6XUaNU6mtNOlaM0K6K6ZoPjEzAlMCR0ikhoURAAc4OJmS0HDKeeLOdZYTnTEnRrKGucTRgcWioJJEpgbp55GSexhBzwgHohtDiw9OTqmQmRMTnKWpAHrIxxIYwgOd1jprQNbKp/dznsTYsYAZ4WnNocC9/VdN7tE6bJtyUdlszS4McTidIAAAhsyOtMjRq2VUUsAD/KNWCtB557cq5tMxrBD7VDqWmjmtmWijWyE8PSMya120E6KjFjHDIyNJVFQNQOpSwiSJBhcS7MachhJAnKuU88OpQxnUqAJ6BopmczVMRTcprO6qgKfCzTEabktfbrLaGuB6Lug+eWEkTPZQrrEW/MB6LC4EEGbm0ocqLisG7okRzWtFXENE6Cu0rpF32OM2CxkZxL2iRLZkUyqRnJQlGKlr8lN3HS+DUtvqE4uJm3VicyvYHU7Uixtta5pAa509PQnuzG9eWbs2mxYAAiBxoGvhknUASStsb0gnKKz5Q9K517WiHrMimf8AiGy4AtCmbcs6+03u3uhP+tFK3kgpcmMcmuDai3wy89NuZ0jdrUxtTPOHELDR7mdh6NjitIBDS2HCkJiRoyJ6EJiXVHbnDij/AOKJ6AuPJ00ZcM6o5muUdO9tM84cU11qb5w4rlL4TxmHDfDij+BROhP2/Jf/AMVF9F9zf9R9jb8lrWxotJLgJ2qIanR0aou68GHJ091fBc8uiPZ2Q3mM1xIfOkF7hKTQJvEgK6yi8aKQzC2xODfOcWQnfKxl6rLo4SlbZhZ5KNJG4s0OYFM+Kv3a3AXONA1pNRqE6Lk7osY0aGwt1pjvI7G0SsbFAOK2RBqkXAdpfEM+C9FOlRw6N7YfvS8/xyAW+SyKB2hvqV0305ZOy2iG0tdGjue9rZEh2IAmWKQDMt5VptvD6QWxoh97Dn4GfcuWWGR6EeoijSwb2OkK2y+MOtAbPct4ObiECQ1Oe1ru1pU34JvAZ2UndEhf8ln05o36+N+TSwL/AFdhX006VjnWG2NE32VzRrL4QHEvQuLeoDsJmDvBHFpIPFOpeQ1Y35OmRIsGKJPax4IycA4cCqL+S1ifIiAGkGYLHPZIilMJAFFioVucKglFLNfUQaUamg0RY+8PY4hzxwYzmyFGvALRLKRbhIGlYLlBdEazRvdRhZI4HNMw8SkQ0mRmZ1nUT0yXSm35ElUTTLaWWlhhRmAtcMjoOgtOg7VqOV3uTn06rY5XCh4nDCQzo9Jwca4gAWgzkSdIMql0zJV4om55eZyLpunPE6sukJ1JrqMs0WvK5HWZ8quBJ5p9ZAZuc4AUc0apZT2ILaos5NGTZ9pPWM+wcN66U74OOSadMYxlSBVp0y6Tc5EjsmZGSpuEpg5jRtGac9MBqtGRYVmc4TaJ1lKYmjV13GQQ95FMmivEotyGu4RRaYculzIcDqdjm2R7AlhPw0KnJvwUxxTdsla3AQRm0gjeKhdDY4PaHjJwBG41WCbULTclrZihmGc4Zp8UzlwM+5RjyXyx2tHrycREMtQXlLb5c4ZjQF5aIijkZEPUvA9rSf8AcTv7G2sdW2NO+H65qngGpIYelU1k9JYicl7yHVtEFw2iX+0VA64LyGZgO/eI9ASjFoe4fvFII0UZRYny3etLUvYdMgdc94j9BCO5/wBteFmvEf8ApR2RB/zVtttjjKNE+UT4pzb3tAyiu7Q0+IStew9wRbYVtcwtfYnunoxTbOYNQM+KgbcF5xc4bIY98W/aK0Tb9tI8sHexvqUov+0g1wEfE9RS7fYO73AsH2Po7vz1q3tYHEdhJA7kSsnsdWZvWMSIdrpD6MlHbuWFoacIZDyFS1xznoxIRaL7tUXrRnAamnAPoyWtSFpZsIdyWOzyJZAZqLw0u7C+qWNyps0OjXOfLQxlOJkFg2w6zNTrKcQjUPSai0ct3/ooIG17p9wl4oXaeU9rfnFwDUwBvfn3oViCjdFGhK2OkPtBc8ze5zjrcS48Shd4xjDk5pIqMvBWbVFcG0pn4FZq1RXOPScTvK1GN7hKVF5nKGO0ZtO9o9ElO3lVFFcDD2OHpQCMdCR+S24J+DKySXk6jyftRjwmxDITJmAciDKXp7UZiQBI1r3ALmXJK+OYfhd+bfLF706Hj07F0J0UYD0pggGYM5t2LkyQ0y+x6GLIpx+5JbWMisMF7A4HMzkRqI2rmHKC6H2Z8j0mO6kTQ4ajqcNS3jrxbIyBnr27UI5TWt0aG5sgOjOQ0lpnPet45NMnmxqSvyYQlRhPCYRVdRwnRvY0IMSIQJfi0MGuZDiCUnKix4IuICj69vlevtTfYqHTjf5I/wBQrT37Yucgu1t6TezMdo9ClLk1B0Y+xmiJ3FaebtDZ5PGA7zItPEd6EWYqSLOYcMwZjeMlB7M7UrjRrL2pE7AvKO3WkOLX6Hsa7iJry0zmRCLW3SDwXhaW6+4puAJDDTMk4tDPOCaYzdY4qAw03mwgC1iGscQvSVYwAk5gIAuBq8KiqqCFvTLUw4DU8ZaUhlO9xJ/D0qsxygcHFxmSd5JVmFBktpCscYuoJpBKfhTw1MCAQ15wAqVZEFMtMPoOl5p8Ehg10drw4NnIA1WdiiqPWBnRednrQO06VZKiLdg+Kap0TIJjs06JkFoRJZitjyKtznF8AywtaXtOkdIAt2ibprGWfNafkgzCY0U6GhgOmbjMy7G96nkVxLYG1NBqE2fObJS9Pgqx8g6xJNsrzzbnTo4nDsaDhz3gntTJ9JrTmG4u8Z8VCjs1GRt8HBFe0ZA03GqrOzV29z7s7s8AqhGS6VwcEuWdG9jFsokWX6lv1yto0ArE+xW6cSMfgv8AcK3LG5qcuQRziLDwRXs1OI4FTPFFb5U2fBaMWh4Du0UPhPtVQGijNbnbidonstqtjmhkCIIbIYwzaxhc8kk9Jz55UAAy7V5E+SVshw+dEQZlpEp++nkRsXleE9kceSHc9ib2udaXmSr7WJcKiaBphO2L3NnV3ogG6Dx1rwAQMH4DqSBp1FEubXuZQAO7DwUVrqw5oq6CoLcyjdrh6UAZtkPOimEFSsGSfJbAY2GE7CnLxKAGOVe1mTHH3p8FYKiiw8Qw66cUkMFWNkoZ2j/is5bTmtXHzcBkGn6zVk7zo6S6mjnB5Tn6E0mqVyQDoZqr0K8Hww9rCJPEjScs5EajUofDU0VA06ZsY9ohYfc3s5uG0GQdUNGUx2cVnIF8FsYxHCYIwls64dh10mhKUrCgkUllbomtkfG9zgJAmYGoaEydFGU4FaJ2dE9ifrRP8r/cK3jdK5x7FdrAjxIZzdC6O8OBI4V7CuhtdUqcuRgHlrZ5w2PHkvkdzh6wFnIWS2PKIA2eIDSkxvBBHeFjbO6ilkR1YHsNc4g0n2LyfFFV5Tss4o2gSzSJVU4jwTHQQU8DPxXpoaHYjWS0lKvTXkgHBVrbk3448CrAKgt2TPj/AMLkmNAJraBSJjE9bA8mpxSFACSUMeJhBd5teCnVW2ibXbj4IQFKwML2vefObwnM+Cyd5Pm4nWVt7AzDZ4jjlIeB/lxWFvA17V0s5ymc15y8vFIYrM1PGKrsVh2SYiApEr0iQzxStCROGU0DLF32lzHh0Nxa6ZAcMxNpHpT/AO0dry9sxhsERw8CqjTKW+a2cSytEJkSFDhiYH6MEzIrWWtZboKMhEvi0HrR4rpGfSiPI4ErY3LFD4ghmbejjnKdMIdIDXJOiwWybNoJJkAxoMzKcstSswLv5p+ISDt1doOgjuU5NPkriUr7S2bK06XDeJz4JFG6O7yWsHYT9Y0XlPsLr1TUySlG7Tyewvc0RMjLqfaUYuM/rPo/aTOcEAryL/gP4T6P8178CH9Z9D7SYAcFeBRj8B/CfR+0vfgL4T6P2lkYJYVXt56vxj3Mcj7bj+E+j/NQ2q4J4fdMp+RraR521AzGNT0fHJj4X6H2l48mPhfofaWgM+vFaAcmPhfofaXjyZ+F+h9pAjPKC0MmCNYlxWoHJj4X6H2k3+y5mDzun9X9pC5GZm0vDbMWDPok6pTMuAAXPbd1iuy3nyYnDLRFlN2eDUABTEslaPY7LnE+2h8yf+xdEpxIKLOflIt5/duf2ofMf1F7+7Y/tQ+Y/qLOuJrSzBtVl+XYtmPY2P7UPmP6ild7HRlL20PmT/2J60LSzn7k1b0+xuf2ofMf1En92x/ah8x/US1oelmEC800W7HsbH9qHzH9Re/u2P7UPmP6iNaDSzCE13LW3MDFs2Fgm9p0mTS2ue6h7d6u/wB2p/ah8x/URm7OQroDejaZl+fuUhLUBj2DSk5IEiCw2hjA3yn5F5AFfegUFKTzkArbo2I9iS1ciiIrSy0ESIxTYSHdmMAIs3kwZS57t5v7SjM6scogdzBSiRa+5eQ/PBxdaCMJAGGGO2c3FeU9JX1In//Z" alt="陳小明 專業形象照">
                </div>
                
                <div class="profile-text">
                    <h1>王小明 (Xiao-Ming Wang)</h1>
                    <p class="headline">資深數位行銷經理 | 專注於品牌增長與數據分析</p>
                    <p class="contact-info">
                        台北市, 台灣 | 
                        <a href="mailto:xiaoming.wang@email.com">xiaoming.wang@email.com</a>
                        <a href="https://linkedin.com/in/xiaomingwang" target="_blank">LinkedIn</a>
                        <a href="https://yourwebsite.me" target="_blank">個人網站</a>
                    </p>
                </div>
            </div>
        </section>

        <section class="about-section">
            <h2>關於我</h2>
            <p>
                擁有 8 年數位行銷經驗的資深經理，專注於品牌行銷戰略、數位增長與用戶數據分析。擅長運用跨部門資源主導大型專案，並透過數據洞察推動業務增長。對行銷科技與數據驅動的決策充滿熱情。
            </p>
            <p>
                目前正尋求能夠發揮品牌管理與數據分析優勢的挑戰性機會。
            </p>
        </section>

        <section class="experience-section">
            <h2>工作經歷</h2>

            <div class="experience-item">
                <div class="experience-logo">Logo</div> <div class="experience-content">
                    <h3>資深行銷經理</h3>
                    <p class="company-dates">
                        大華科技公司 (台北市) | 
                        <span>2018年9月 - 至今</span>
                    </p>
                    <ul>
                        <li>主導並執行 20+ 大型品牌行銷專案，將品牌知名度提升 30%。</li>
                        <li>建立數據分析團隊，透過用戶行為分析提高行銷 ROI 50%。</li>
                        <li>跨部門溝通協調，帶領 5 人團隊完成產品發表會。</li>
                        <li>年度預算管理 1000萬 NTD。</li>
                    </ul>
                </div>
            </div>

            <div class="experience-item">
                <div class="experience-logo">Logo</div> <div class="experience-content">
                    <h3>行銷專員</h3>
                    <p class="company-dates">
                        新創有限公司 (台北市) | 
                        <span>2015年6月 - 2018年8月</span>
                    </p>
                    <ul>
                        <li>負責社群媒體營運與內容行銷，將追蹤人數增加 200%。</li>
                        <li>規劃並執行網路廣告 (Google Ads, FB Ads) 活動。</li>
                        <li>分析行銷數據並製作週報、月報。</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="skills-section">
            <h2>核心技能</h2>
            <ul class="skills-list">
                <li>品牌行銷</li>
                <li>數位行銷 (SEO/SEM)</li>
                <li>數據分析</li>
                <li>專案管理</li>
                <li>跨部門溝通</li>
                <li>行銷科技 (MarTech)</li>
                <li>用戶行為洞察</li>
                <li>團隊領導</li>
            </ul>
        </section>

        <section class="projects-section">
            <h2>專案經驗</h2>
            <div class="project-item">
                <h3>行銷自動化平台導入專案 (大華科技)</h3>
                <p>
                    擔任主要負責人，成功整合 CRM 系統並導入 HubSpot 自動化平台，將潛在客戶轉化率提升 15%。
                </p>
            </div>
        </section>

        <section class="education-section">
            <h2>學歷</h2>
            <div class="education-item">
                <h3>國立台北大學</h3>
                <p>企業管理學系, 碩士</p>
                <p class="company-dates">2013年 - 2015年</p>
            </div>
            <div class="education-item">
                <h3>國立台灣科技大學</h3>
                <p>工商管理學系, 學士</p>
                <p class="company-dates">2009年 - 2013年</p>
            </div>
        </section>

        <div class="footer">
            &copy; 2024 陳小明. 專業介紹網頁 - 單一檔案 Data URI 嵌入版
        </div>

    </div>

</body>
</html>
