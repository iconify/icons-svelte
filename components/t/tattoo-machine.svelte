<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0dj8vbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r0dj8vbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tattoo-machine" {...props}></Icon>
