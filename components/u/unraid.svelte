<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atsgvzujm.css';
import '../../css/a/a-w0k537t.css';
import '../../css/i/iid5rgj_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGBsmEEePQ" x1="0" x2="1" y1="0" y2="0"><stop offset="0" class="atsgvzujm"/><stop offset="1" class="a-w0k537t"/></linearGradient></defs><path fill="url(#SVGBsmEEePQ)" class="iid5rgj_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:unraid" {...props}></Icon>
