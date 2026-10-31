<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk9e17sjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9e17sjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:terminal-gloss" {...props}></Icon>
