<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjm2rybfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjm2rybfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tinder" {...props}></Icon>
