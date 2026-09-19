<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baqmotbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="baqmotbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-amount-up" {...props}></Icon>
