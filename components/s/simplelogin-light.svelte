<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyucu1t5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyucu1t5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:simplelogin-light" {...props}></Icon>
