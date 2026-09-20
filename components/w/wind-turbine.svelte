<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k20y2qbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k20y2qbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wind-turbine" {...props}></Icon>
