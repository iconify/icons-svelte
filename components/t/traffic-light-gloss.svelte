<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp9ph3m6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp9ph3m6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:traffic-light-gloss" {...props}></Icon>
