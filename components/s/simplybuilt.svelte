<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnkm-ebgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1600};
const content = `<path class="fnkm-ebgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:simplybuilt" {...props}></Icon>
