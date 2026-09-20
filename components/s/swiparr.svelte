<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl6gyl07q.css';
import '../../css/h/hxv6wjbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yl6gyl07q"/><path class="hxv6wjbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swiparr" {...props}></Icon>
