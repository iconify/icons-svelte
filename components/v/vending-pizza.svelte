<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2qzlccvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e2qzlccvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-pizza" {...props}></Icon>
