<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yasl903_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yasl903_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sid" {...props}></Icon>
