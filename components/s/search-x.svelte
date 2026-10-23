<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbnm49bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbnm49bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:search-x" {...props}></Icon>
