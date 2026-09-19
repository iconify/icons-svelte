<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrnwts-5v.css';
import '../../css/t/t0dn9ubiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g transform="translate(-173.29 -80.936)scale(3.77953)"><rect class="yrnwts-5v"/><path class="t0dn9ubiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yunohost" {...props}></Icon>
