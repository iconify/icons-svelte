<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-twxbb6x.css';
import '../../css/z/zt62pibkv.css';
import '../../css/f/fb6cqib6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-twxbb6x"/><rect class="zt62pibkv"/><path class="fb6cqib6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trash-bin-outline" {...props}></Icon>
