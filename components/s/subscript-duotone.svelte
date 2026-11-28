<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jozev15so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jozev15so primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:subscript-duotone" {...props}></Icon>
