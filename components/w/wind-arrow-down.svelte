<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzhp5pbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzhp5pbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wind-arrow-down" {...props}></Icon>
