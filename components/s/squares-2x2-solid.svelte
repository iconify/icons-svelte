<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzqs9yb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzqs9yb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:squares-2x2-solid" {...props}></Icon>
