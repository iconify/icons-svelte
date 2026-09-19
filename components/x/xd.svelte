<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y19ixtbyb.css';
import '../../css/r/r_go1j2mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y19ixtbyb"/><path class="r_go1j2mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:xd" {...props}></Icon>
