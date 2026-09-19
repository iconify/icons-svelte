<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qill-ebtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qill-ebtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:volume-low" {...props}></Icon>
