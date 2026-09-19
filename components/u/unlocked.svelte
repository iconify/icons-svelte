<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvch9ib1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="yvch9ib1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:unlocked" {...props}></Icon>
