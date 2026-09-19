<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u-tqjdofv.css';
import '../../css/m/m2kr2vb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="u-tqjdofv"/><path class="m2kr2vb1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-instagram" {...props}></Icon>
