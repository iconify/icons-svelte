<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz12-ibde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jz12-ibde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-candles" {...props}></Icon>
