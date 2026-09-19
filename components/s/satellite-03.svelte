<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w5yxk8b6x.css';
import '../../css/c/cau_lwbjl.css';
import '../../css/k/knoqyn-wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="w5yxk8b6x"/><path class="cau_lwbjl"/><path class="knoqyn-wa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:satellite-03" {...props}></Icon>
