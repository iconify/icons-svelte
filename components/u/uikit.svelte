<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x00vtyb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x00vtyb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:uikit" {...props}></Icon>
