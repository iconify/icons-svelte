<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5envbbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5envbbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-hide-line" {...props}></Icon>
