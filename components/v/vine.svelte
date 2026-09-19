<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqskrdctq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqskrdctq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vine" {...props}></Icon>
