<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb05267ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb05267ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wallos-light" {...props}></Icon>
