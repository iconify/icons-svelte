<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/ycpx6cc1w.css';
import '../../css/d/dpom0hb5y.css';
import '../../css/p/pbm76tdaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ycpx6cc1w"/><path class="dpom0hb5y"/><path class="pbm76tdaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:video-ai" {...props}></Icon>
