<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x26ijbb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x26ijbb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:snowmobile" {...props}></Icon>
