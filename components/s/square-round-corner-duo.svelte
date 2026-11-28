<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roxidabpe.css';
import '../../css/n/nckoucbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roxidabpe secondary"/><path class="nckoucbbw primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-round-corner-duo" {...props}></Icon>
