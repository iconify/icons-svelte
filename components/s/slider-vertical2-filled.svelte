<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xja7l4brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xja7l4brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-vertical2-filled" {...props}></Icon>
