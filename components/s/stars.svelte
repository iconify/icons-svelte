<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/ga2-w1vzn.css';
import '../../css/z/z8owmn-2i.css';
import '../../css/r/rga5hfpvp.css';
import '../../css/g/g69fedczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ga2-w1vzn"/><path class="z8owmn-2i"/><path class="rga5hfpvp"/><path class="g69fedczw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stars" {...props}></Icon>
