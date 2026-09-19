<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/oyx227b1q.css';
import '../../css/j/jap9g-nus.css';
import '../../css/w/wzt-yrb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="oyx227b1q"/><path class="jap9g-nus"/><path class="wzt-yrb2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:structure-folder-circle" {...props}></Icon>
