<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zddt3ibfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zddt3ibfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trash-simple-bold" {...props}></Icon>
