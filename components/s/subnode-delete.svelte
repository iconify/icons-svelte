<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bu8_8lune.css';
import '../../css/y/ygxy_c58d.css';
import '../../css/e/eh32i2zgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bu8_8lune"/><path class="ygxy_c58d"/><path class="eh32i2zgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:subnode-delete" {...props}></Icon>
