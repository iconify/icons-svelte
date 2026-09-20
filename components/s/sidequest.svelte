<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frkl9z0ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frkl9z0ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sidequest" {...props}></Icon>
