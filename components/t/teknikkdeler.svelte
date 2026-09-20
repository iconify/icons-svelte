<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yevpafbzb.css';
import '../../css/t/tzflgcclh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yevpafbzb"/><path class="tzflgcclh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teknikkdeler" {...props}></Icon>
