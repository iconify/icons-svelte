<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgqka1bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgqka1bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:three-d-cube-filled" {...props}></Icon>
