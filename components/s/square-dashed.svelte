<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s146rvdmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s146rvdmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-dashed" {...props}></Icon>
