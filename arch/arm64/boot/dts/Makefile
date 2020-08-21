dtb-y += exynos7420-zenlte_kor_00.dtb
dtb-y += exynos7420-zenlte_kor_01.dtb
dtb-y += exynos7420-zenlte_kor_02.dtb
dtb-y += exynos7420-zenlte_kor_03.dtb
dtb-y += exynos7420-zenlte_kor_04.dtb
dtb-y += exynos7420-zenlte_kor_09.dtb

targets += dtbs
DTB_LIST	:= $(dtb-y) $(dtbo-y)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
