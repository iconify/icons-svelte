<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj-4iwbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yj-4iwbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:socket-io" {...props}></Icon>
