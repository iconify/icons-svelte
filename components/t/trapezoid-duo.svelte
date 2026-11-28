<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk5p8su9s.css';
import '../../css/m/mxptukb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yk5p8su9s"/><path class="mxptukb2q primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trapezoid-duo" {...props}></Icon>
