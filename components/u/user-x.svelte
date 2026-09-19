<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa2012box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa2012box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:user-x" {...props}></Icon>
