<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzabj504c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nzabj504c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shlink-light" {...props}></Icon>
