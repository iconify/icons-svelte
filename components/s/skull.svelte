<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c23hjf9vn.css';
import '../../css/z/z_gk1_m8o.css';
import '../../css/y/yq0t3ucke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c23hjf9vn"/><path class="z_gk1_m8o"/><path class="yq0t3ucke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:skull" {...props}></Icon>
