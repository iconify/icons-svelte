<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgfb0wb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgfb0wb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:smartthings" {...props}></Icon>
