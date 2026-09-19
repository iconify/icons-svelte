<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8vwuw0xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m8vwuw0xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:volume-medium" {...props}></Icon>
