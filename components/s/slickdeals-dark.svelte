<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvfovab-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fvfovab-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slickdeals-dark" {...props}></Icon>
