<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b76t4jl9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b76t4jl9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ugreen-nas-light" {...props}></Icon>
