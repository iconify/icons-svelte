<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-vu5ccny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-vu5ccny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:widget6-filled" {...props}></Icon>
