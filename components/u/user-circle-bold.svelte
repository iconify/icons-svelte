<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/grc9tmbtv.css';
import '../../css/q/qi-z61bjd.css';
import '../../css/g/goueu-bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="grc9tmbtv"/><path clip-rule="evenodd" class="qi-z61bjd"/><path clip-rule="evenodd" class="goueu-bkx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:user-circle-bold" {...props}></Icon>
