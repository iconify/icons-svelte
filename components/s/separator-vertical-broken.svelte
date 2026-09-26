<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/l678ypbwk.css';
import '../../css/m/mwz2inb5v.css';
import '../../css/x/x1f4lc3zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l678ypbwk"/><path class="mwz2inb5v"/><path class="x1f4lc3zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:separator-vertical-broken" {...props}></Icon>
