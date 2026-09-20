<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ar5ibre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7ar5ibre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sliders-filled" {...props}></Icon>
