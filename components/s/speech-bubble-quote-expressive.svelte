<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a1i0eabhl.css';
import '../../css/y/yu1ky3bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a1i0eabhl"/><path clip-rule="evenodd" class="yu1ky3bap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:speech-bubble-quote-expressive" {...props}></Icon>
