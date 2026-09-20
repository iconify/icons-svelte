<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds8oc_btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ds8oc_btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-people-standing-in-rectangle-under-arrow-up-beside-arrow-down" {...props}></Icon>
