<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anhh36llh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anhh36llh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wind-turbine-success" {...props}></Icon>
