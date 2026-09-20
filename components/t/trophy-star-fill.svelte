<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydce0w0ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydce0w0ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trophy-star-fill" {...props}></Icon>
