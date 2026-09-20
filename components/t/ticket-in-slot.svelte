<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwk7x1aeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iwk7x1aeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ticket-in-slot" {...props}></Icon>
