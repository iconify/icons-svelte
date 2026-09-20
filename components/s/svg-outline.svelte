<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xna70pbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xna70pbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:svg-outline" {...props}></Icon>
