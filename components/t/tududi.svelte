<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd0tezbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zd0tezbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tududi" {...props}></Icon>
