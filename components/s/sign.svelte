<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmpt56yqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xmpt56yqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sign" {...props}></Icon>
