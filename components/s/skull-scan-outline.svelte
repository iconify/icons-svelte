<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhn1d58yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhn1d58yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skull-scan-outline" {...props}></Icon>
