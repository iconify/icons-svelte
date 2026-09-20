<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi0nwc0pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi0nwc0pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:selector-vertical-line" {...props}></Icon>
