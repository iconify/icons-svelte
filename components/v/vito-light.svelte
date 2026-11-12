<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb0snb0al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yb0snb0al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vito-light" {...props}></Icon>
