<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoqz64bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoqz64bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sleep-off" {...props}></Icon>
