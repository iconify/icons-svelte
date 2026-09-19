<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz6zp-afy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rz6zp-afy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:triangle-down" {...props}></Icon>
