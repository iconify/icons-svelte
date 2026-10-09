<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srxxy_b0g.css';
import '../../css/v/va3-tmdaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="srxxy_b0g"/><path class="va3-tmdaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunset-48-bold" {...props}></Icon>
