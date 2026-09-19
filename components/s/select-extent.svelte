<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhwv4f-bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vhwv4f-bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:select-extent" {...props}></Icon>
