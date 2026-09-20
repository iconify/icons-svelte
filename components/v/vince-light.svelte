<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug7066bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ug7066bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vince-light" {...props}></Icon>
