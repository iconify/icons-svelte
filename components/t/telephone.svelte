<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xkadzabjm.css';
import '../../css/y/y-aykgvmv.css';
import '../../css/i/ivgr-ipsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xkadzabjm"/><path class="y-aykgvmv"/><path class="ivgr-ipsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:telephone" {...props}></Icon>
