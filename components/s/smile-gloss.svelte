<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p04vnh08p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p04vnh08p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smile-gloss" {...props}></Icon>
