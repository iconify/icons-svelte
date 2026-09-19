<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a23d2obbm.css';
import '../../css/g/gj72yxbju.css';
import '../../css/x/xpke-abpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="a23d2obbm"/><path clip-rule="evenodd" class="gj72yxbju"/><path class="xpke-abpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-fast-bold" {...props}></Icon>
