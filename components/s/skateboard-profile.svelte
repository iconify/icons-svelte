<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czticys6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="czticys6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skateboard-profile" {...props}></Icon>
