<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2ejlac0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n2ejlac0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:simplybuilt" {...props}></Icon>
