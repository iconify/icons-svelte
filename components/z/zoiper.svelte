<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpw3oirif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpw3oirif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zoiper" {...props}></Icon>
