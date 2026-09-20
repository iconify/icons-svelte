<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq60ccc1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lq60ccc1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stratovolcano" {...props}></Icon>
