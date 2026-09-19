<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szgw_9b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="szgw_9b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-end" {...props}></Icon>
