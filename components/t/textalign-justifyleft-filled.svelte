<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c97p6wa7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c97p6wa7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-justifyleft-filled" {...props}></Icon>
