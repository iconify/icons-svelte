<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2mhuoqew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2mhuoqew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:up-arrow" {...props}></Icon>
