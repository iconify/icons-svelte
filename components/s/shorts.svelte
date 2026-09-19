<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ij70iuc0v.css';
import '../../css/c/cnjpn0b_x.css';
import '../../css/l/la0y6bzzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ij70iuc0v"/><path class="cnjpn0b_x"/><path class="la0y6bzzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:shorts" {...props}></Icon>
