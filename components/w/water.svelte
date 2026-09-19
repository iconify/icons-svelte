<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iolobs1xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iolobs1xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water" {...props}></Icon>
