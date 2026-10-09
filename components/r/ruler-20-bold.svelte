<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwee6s4xt.css';
import '../../css/g/grkcr9m5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vwee6s4xt"/><path class="grkcr9m5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruler-20-bold" {...props}></Icon>
