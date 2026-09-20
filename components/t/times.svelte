<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3s1a1w6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3s1a1w6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:times" {...props}></Icon>
