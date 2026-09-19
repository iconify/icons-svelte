<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_nj_bik.css';
import '../../css/y/yfbdwob5o.css';
import '../../css/y/yo40yrbuz.css';
import '../../css/c/ce9c_jbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vh_nj_bik"/><path class="yfbdwob5o"/><path class="yo40yrbuz"/><path class="ce9c_jbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:slack" {...props}></Icon>
