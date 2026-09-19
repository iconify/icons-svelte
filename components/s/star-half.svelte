<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upwf8cbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upwf8cbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:star-half" {...props}></Icon>
