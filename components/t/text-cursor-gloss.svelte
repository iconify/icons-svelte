<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfbjdmbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbjdmbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:text-cursor-gloss" {...props}></Icon>
