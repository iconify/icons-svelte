<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik89tg8wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik89tg8wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zoom-in-gloss" {...props}></Icon>
