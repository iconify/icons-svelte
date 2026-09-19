<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/ljakav41z.css';
import '../../css/g/gplkv5ukx.css';
import '../../css/y/yf-u9nb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ljakav41z"/><path class="gplkv5ukx"/><path class="yf-u9nb-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:spaceship" {...props}></Icon>
