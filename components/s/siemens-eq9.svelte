<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4lkbuben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4lkbuben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:siemens-eq9" {...props}></Icon>
