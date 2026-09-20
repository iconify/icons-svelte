<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_v0kzl5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_v0kzl5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-passenger-variant" {...props}></Icon>
