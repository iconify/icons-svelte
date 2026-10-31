<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ria-2-bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ria-2-bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tv-gloss" {...props}></Icon>
