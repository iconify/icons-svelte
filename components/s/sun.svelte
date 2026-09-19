<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7bk_fbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x7bk_fbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sun" {...props}></Icon>
