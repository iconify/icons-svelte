<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkpaxnb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkpaxnb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:unlink-outline" {...props}></Icon>
