<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i13mkabts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i13mkabts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-low2-filled" {...props}></Icon>
