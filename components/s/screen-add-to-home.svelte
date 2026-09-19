<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/x/xm3as_bdr.css';
import '../../css/g/gokw35m3p.css';
import '../../css/r/re9a3j93t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xm3as_bdr"/><path class="gokw35m3p"/><path class="re9a3j93t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:screen-add-to-home" {...props}></Icon>
