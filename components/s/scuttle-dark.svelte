<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkfdg3zno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkfdg3zno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scuttle-dark" {...props}></Icon>
