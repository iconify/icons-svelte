<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jalhqjb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jalhqjb9h primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:strikethrough-duotone" {...props}></Icon>
