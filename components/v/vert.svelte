<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo0p6m5ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bo0p6m5ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vert" {...props}></Icon>
