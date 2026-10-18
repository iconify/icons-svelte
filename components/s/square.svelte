<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb8m3n93e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb8m3n93e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square" {...props}></Icon>
