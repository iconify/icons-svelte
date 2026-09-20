<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pq6j9o11h.css';
import '../../css/c/czssrseqz.css';
import '../../css/s/ss0-xmbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pq6j9o11h"/><path clip-rule="evenodd" class="czssrseqz"/><path class="ss0-xmbxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tower" {...props}></Icon>
