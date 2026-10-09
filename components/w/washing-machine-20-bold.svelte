<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmo-gj4um.css';
import '../../css/t/t0j6e-buy.css';
import '../../css/d/dw-imwo_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wmo-gj4um"/><path class="t0j6e-buy"/><path class="dw-imwo_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:washing-machine-20-bold" {...props}></Icon>
