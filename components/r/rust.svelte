<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaiyq5bvp.css';
import '../../css/g/gfjx0h0sh.css';
import '../../css/h/hgv6-1_gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="gfjx0h0sh"/><path class="hgv6-1_gy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:rust" {...props}></Icon>
