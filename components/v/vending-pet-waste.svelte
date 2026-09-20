<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4g_3efpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o4g_3efpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-pet-waste" {...props}></Icon>
