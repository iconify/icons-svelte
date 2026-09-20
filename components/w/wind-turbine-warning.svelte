<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4zflabkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4zflabkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wind-turbine-warning" {...props}></Icon>
