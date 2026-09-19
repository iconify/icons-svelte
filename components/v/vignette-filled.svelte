<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfvnc4bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfvnc4bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vignette-filled" {...props}></Icon>
