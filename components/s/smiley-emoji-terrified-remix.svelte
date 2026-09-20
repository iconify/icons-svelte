<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp4sxebmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fp4sxebmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-emoji-terrified-remix" {...props}></Icon>
