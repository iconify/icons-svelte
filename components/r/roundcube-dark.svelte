<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dki4pzb1t.css';
import '../../css/c/clec0e7ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dki4pzb1t"/><path class="clec0e7ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roundcube-dark" {...props}></Icon>
