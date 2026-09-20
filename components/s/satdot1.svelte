<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foxcxt4ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foxcxt4ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:satdot1" {...props}></Icon>
