<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uor33c4rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uor33c4rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spoon-line" {...props}></Icon>
