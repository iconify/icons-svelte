<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzu4d0kby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzu4d0kby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:surround-sound-7-1" {...props}></Icon>
