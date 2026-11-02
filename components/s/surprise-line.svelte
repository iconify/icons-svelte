<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4c6iab5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4c6iab5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:surprise-line" {...props}></Icon>
