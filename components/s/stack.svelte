<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfx6ry1aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jfx6ry1aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:stack" {...props}></Icon>
