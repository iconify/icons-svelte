<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg8_2jbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wg8_2jbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-giraffes" {...props}></Icon>
