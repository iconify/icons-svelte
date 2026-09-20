<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn7escblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cn7escblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zed" {...props}></Icon>
