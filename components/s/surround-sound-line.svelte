<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmen-absx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmen-absx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:surround-sound-line" {...props}></Icon>
