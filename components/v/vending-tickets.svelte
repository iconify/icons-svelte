<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot3vn1bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ot3vn1bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-tickets" {...props}></Icon>
