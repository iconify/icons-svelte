<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h36wngbkh.css';
import '../../css/b/b29c1cwoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h36wngbkh"/><path class="b29c1cwoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:water-outline" {...props}></Icon>
