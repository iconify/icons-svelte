<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xug1g_b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xug1g_b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:squint-smiling-face" {...props}></Icon>
