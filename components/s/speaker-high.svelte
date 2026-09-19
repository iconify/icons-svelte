<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cay9w4bva.css';
import '../../css/a/ad3u9_-bp.css';
import '../../css/a/ahgurpb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cay9w4bva"/><path class="ad3u9_-bp"/><path class="ahgurpb-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:speaker-high" {...props}></Icon>
