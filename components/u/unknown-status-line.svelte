<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwe8g8bcu.css';
import '../../css/f/fcrmxtbfx.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-outline clr-i-outline-path-1 xwe8g8bcu"/><path class="clr-i-outline clr-i-outline-path-2 fcrmxtbfx"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:unknown-status-line" {...props}></Icon>
