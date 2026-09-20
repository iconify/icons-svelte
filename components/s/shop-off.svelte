<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhm3v8bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhm3v8bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-off" {...props}></Icon>
