<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_o8_ue3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e_o8_ue3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:town-15" {...props}></Icon>
