<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p1uypcbqv.css';
import '../../css/g/g7f03lbok.css';
import '../../css/m/m-u0l2bzu.css';
import '../../css/s/snq0_74tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="p1uypcbqv"/><path class="g7f03lbok"/><path clip-rule="evenodd" class="m-u0l2bzu"/><rect class="snq0_74tm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ying-yang-bold" {...props}></Icon>
