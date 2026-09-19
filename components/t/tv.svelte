<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arx8vnbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="arx8vnbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:tv" {...props}></Icon>
