<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wx9jfdcbr.css';
import '../../css/s/sos1_8pee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wx9jfdcbr"/><path clip-rule="evenodd" class="sos1_8pee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:tv-dot-solid" {...props}></Icon>
