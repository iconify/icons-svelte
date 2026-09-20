<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih0p_rboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ih0p_rboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:y-junction" {...props}></Icon>
