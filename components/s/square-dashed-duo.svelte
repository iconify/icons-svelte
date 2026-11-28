<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-78pm1dc.css';
import '../../css/s/s146rvdmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-78pm1dc secondary"/><path class="primary s146rvdmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-dashed-duo" {...props}></Icon>
