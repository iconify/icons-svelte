<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxut5rbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxut5rbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-dashed-duo" {...props}></Icon>
