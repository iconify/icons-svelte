<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze2jbkbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze2jbkbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:window-lock" {...props}></Icon>
