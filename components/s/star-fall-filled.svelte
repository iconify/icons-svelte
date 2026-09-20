<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzi9wnb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzi9wnb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-fall-filled" {...props}></Icon>
