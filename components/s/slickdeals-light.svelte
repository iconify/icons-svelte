<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgrx0uh8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgrx0uh8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slickdeals-light" {...props}></Icon>
