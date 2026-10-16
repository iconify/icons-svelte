<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s900nabfq.css';
import '../../css/w/w5mx-v3dw.css';
import '../../css/m/ma8aecusd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s900nabfq"/><path class="w5mx-v3dw"/><path class="ma8aecusd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trowel-20-bold" {...props}></Icon>
