<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrmfy3bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrmfy3bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:x-add" {...props}></Icon>
