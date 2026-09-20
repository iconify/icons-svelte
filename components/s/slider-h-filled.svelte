<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9fr5jbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9fr5jbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-h-filled" {...props}></Icon>
