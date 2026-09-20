<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buq6-w4ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="buq6-w4ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sitting-tank-toilet-with-droplet" {...props}></Icon>
