<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5s96l9jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5s96l9jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:vibrate-off" {...props}></Icon>
