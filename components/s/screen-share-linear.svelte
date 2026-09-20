<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e71p8bxkf.css';
import '../../css/g/g_eh3ebdg.css';
import '../../css/z/zgwn8jw0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e71p8bxkf"/><path class="g_eh3ebdg"/><path class="zgwn8jw0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screen-share-linear" {...props}></Icon>
