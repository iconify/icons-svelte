<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsaapz8jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsaapz8jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:study-room" {...props}></Icon>
