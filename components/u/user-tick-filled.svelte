<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhxve18yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhxve18yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-tick-filled" {...props}></Icon>
