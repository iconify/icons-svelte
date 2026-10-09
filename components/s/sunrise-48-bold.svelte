<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srxxy_b0g.css';
import '../../css/b/b9waewb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="srxxy_b0g"/><path class="b9waewb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunrise-48-bold" {...props}></Icon>
