<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv5-8abpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gv5-8abpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:soccer-ball" {...props}></Icon>
