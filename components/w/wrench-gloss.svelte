<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0mc-1bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0mc-1bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrench-gloss" {...props}></Icon>
