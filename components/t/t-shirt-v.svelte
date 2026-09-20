<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j34rt5j7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j34rt5j7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:t-shirt-v" {...props}></Icon>
