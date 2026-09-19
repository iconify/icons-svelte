<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wozg3fb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wozg3fb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:x" {...props}></Icon>
