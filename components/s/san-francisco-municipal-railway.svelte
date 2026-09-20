<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3owobom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3owobom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:san-francisco-municipal-railway" {...props}></Icon>
