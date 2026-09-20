<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ivy0y0brz.css';
import '../../css/q/qldi4nb9l.css';
import '../../css/z/zgwn8jw0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ivy0y0brz"/><path class="qldi4nb9l"/><path class="zgwn8jw0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screen-share-broken" {...props}></Icon>
