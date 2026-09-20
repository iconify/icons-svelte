<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ewnf0czgr.css';
import '../../css/x/x5d6pr60j.css';
import '../../css/e/ee75qzblf.css';
import '../../css/z/zxg-kkqlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ewnf0czgr"/><path class="x5d6pr60j"/><path class="ee75qzblf"/><path class="zxg-kkqlp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-line-bold" {...props}></Icon>
