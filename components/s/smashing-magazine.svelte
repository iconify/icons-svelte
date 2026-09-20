<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yct52e2ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yct52e2ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:smashing-magazine" {...props}></Icon>
