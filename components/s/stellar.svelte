<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlm7a0b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlm7a0b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stellar" {...props}></Icon>
