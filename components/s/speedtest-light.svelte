<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyuqmdb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xyuqmdb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:speedtest-light" {...props}></Icon>
