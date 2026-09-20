<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvx6p_tap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvx6p_tap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:toyota" {...props}></Icon>
