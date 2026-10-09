<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7tm0ry1a.css';
import '../../css/i/ivgem8b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v7tm0ry1a"/><path class="ivgem8b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:supply-chain-20" {...props}></Icon>
