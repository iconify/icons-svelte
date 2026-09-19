<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpol7oimp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpol7oimp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shield-x" {...props}></Icon>
