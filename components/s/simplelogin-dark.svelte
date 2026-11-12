<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kme45abqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kme45abqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:simplelogin-dark" {...props}></Icon>
