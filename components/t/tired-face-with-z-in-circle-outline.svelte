<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1o_wkb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v1o_wkb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-z-in-circle-outline" {...props}></Icon>
