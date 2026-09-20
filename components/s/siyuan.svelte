<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7020pbgf.css';
import '../../css/p/p-fy8svxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d7020pbgf"/><path class="p-fy8svxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:siyuan" {...props}></Icon>
