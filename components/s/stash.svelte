<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izvg8nb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="izvg8nb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stash" {...props}></Icon>
