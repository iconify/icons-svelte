<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itrkz7s2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="itrkz7s2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-basket" {...props}></Icon>
