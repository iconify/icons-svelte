<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_wvbn4-s.css';
import '../../css/b/bfe2smrhu.css';
import '../../css/x/xbdrabtly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="p_wvbn4-s"><path class="bfe2smrhu"/><path class="xbdrabtly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:window" {...props}></Icon>
