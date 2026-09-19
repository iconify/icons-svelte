<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp_4ch6qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="xp_4ch6qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:text-height" {...props}></Icon>
