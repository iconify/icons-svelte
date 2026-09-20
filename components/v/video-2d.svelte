<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya_hj3bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya_hj3bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-2d" {...props}></Icon>
