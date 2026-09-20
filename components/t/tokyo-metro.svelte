<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgiz5hr3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgiz5hr3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tokyo-metro" {...props}></Icon>
