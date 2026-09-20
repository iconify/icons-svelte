<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvz6j0baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvz6j0baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:star-off-line" {...props}></Icon>
