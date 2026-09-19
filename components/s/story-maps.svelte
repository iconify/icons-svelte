<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl3l4tb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tl3l4tb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:story-maps" {...props}></Icon>
