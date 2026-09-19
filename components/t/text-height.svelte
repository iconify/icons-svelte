<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1glutbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1glutbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:text-height" {...props}></Icon>
